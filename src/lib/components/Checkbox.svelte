<script lang="ts">
  import { onMount } from 'svelte';

  let { id }: { id: string } = $props();
  let checked = $state(false);

  const storageKey = `checkbox-${id}`;

  const updateChecked = () => {
    checked = JSON.parse(localStorage.getItem(storageKey) ?? 'false') || false;
  };

  onMount(() => {
    updateChecked();

    // Listen for `storage` event (cross-tab changes)
    const handleStorage = (event: StorageEvent) => {
      if (event.key === storageKey) {
        updateChecked();
      }
    };
    window.addEventListener('storage', handleStorage);

    // Lister for custom event (same-tab changes)
    const handleCustomStorage = (event: CustomEvent) => {
      if (event.detail === storageKey) {
        updateChecked();
      }
    };
    window.addEventListener('localStorageUpdate', handleCustomStorage as EventListener);

    return () => {
      window.removeEventListener('storage', handleStorage);
      window.removeEventListener('localStorageUpdate', handleCustomStorage as EventListener);
    };
  });

  $effect(() => {
    if (checked !== null) {
      localStorage.setItem(storageKey, JSON.stringify(checked));

      // Dispatch a custom event to notify other components in the same tab
      window.dispatchEvent(new CustomEvent('localStorageUpdate', { detail: storageKey }));
    }
  });
</script>

<input type="checkbox" class="checkbox checkbox-sm checkbox-primary" {id} bind:checked />

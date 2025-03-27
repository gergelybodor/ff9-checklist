<script lang="ts">
  import { onMount } from 'svelte';

  let { id }: { id: string } = $props();
  let checked = $state(false);

  onMount(() => {
    checked = JSON.parse(localStorage.getItem(`checkbox-${id}`) ?? 'false') || false;
  });

  $effect(() => {
    if (checked !== null) {
      localStorage.setItem(`checkbox-${id}`, JSON.stringify(checked));
    }
  });
</script>

<input type="checkbox" class="checkbox checkbox-sm checkbox-primary" {id} bind:checked />

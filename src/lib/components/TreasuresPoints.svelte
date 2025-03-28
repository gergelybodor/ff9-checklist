<script lang="ts">
  import { onMount, tick } from 'svelte';

  let points = 0;
  let all = 0;

  const sumPoints = (sum: number, el: HTMLInputElement) => {
    const points = el.attributes.getNamedItem('data-point')?.value === '2' ? 2 : 1;
    return sum + points;
  };

  const countChecked = () => {
    const allCheckboxes = Array.from(document.querySelectorAll('input[type="checkbox"]')).filter(
      (el) => el.id.startsWith('t-')
    ) as HTMLInputElement[];

    all = allCheckboxes.reduce(sumPoints, 0);
    points = allCheckboxes.filter((el) => el.checked).reduce(sumPoints, 0);
  };

  onMount(() => {
    // Wait for checkboxes to be fully rendered
    tick().then(() => {
      countChecked();
    });

    const handleChange = () => countChecked();
    document.addEventListener('change', handleChange);

    return () => {
      document.removeEventListener('change', handleChange);
    };
  });
</script>

{#if all > 0}
  <div class="badge badge-primary outline-base-200 outline-[8px]">Points: {points} / {all}</div>
{/if}

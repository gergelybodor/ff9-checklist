<script lang="ts">
  import { TreasuresPoints } from '$lib';

  const { label }: { label: string } = $props();
</script>

<div class="bg-base-200 flex w-full">
  <div class="relative h-12 w-full">
    <div class="divider">{label}</div>
    <div class="absolute inset-0 z-10 flex h-12 w-1/2 items-center justify-center">
      <TreasuresPoints />
    </div>
  </div>
</div>

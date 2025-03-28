<script lang="ts">
  import {
    TreasuresDisk1,
    MissablesDisk1,
    MissablesDisk2,
    MissablesIntro,
    TreasuresIntro,
    TreasuresDisk2,
    TreasuresDisk3,
    TreasuresDisk4,
    MissablesDisk4,
    MissablesDisk3
  } from '$lib';
</script>

<svelte:head>
  <title>Final Fantasy IX Trophy Guide Checklist</title>
  <meta name="description" content="Final Fantasy IX Trophy Guide Checklist" />
</svelte:head>

<div class="grid grid-cols-2 gap-x-8 gap-y-4 p-8">
  <TreasuresIntro />
  <MissablesIntro />

  <div class="bg-base-200 sticky top-0 z-10 col-span-2">
    <div class="divider">Disk 1</div>
  </div>

  <TreasuresDisk1 />
  <MissablesDisk1 />

  <div class="bg-base-200 sticky top-0 z-10 col-span-2">
    <div class="divider">Disk 2</div>
  </div>

  <TreasuresDisk2 />
  <MissablesDisk2 />

  <div class="bg-base-200 sticky top-0 z-10 col-span-2">
    <div class="divider">Disk 3</div>
  </div>

  <TreasuresDisk3 />
  <MissablesDisk3 />

  <div class="bg-base-200 sticky top-0 z-10 col-span-2">
    <div class="divider">Disk 4</div>
  </div>

  <TreasuresDisk4 />
  <MissablesDisk4 />
</div>

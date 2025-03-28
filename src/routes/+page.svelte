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
    MissablesDisk3,
    Divider
  } from '$lib';
</script>

<svelte:head>
  <title>Final Fantasy IX Trophy Guide Checklist</title>
  <meta name="description" content="Final Fantasy IX Trophy Guide Checklist" />
</svelte:head>

<div class="grid grid-cols-2 gap-x-8 gap-y-4 p-8">
  <TreasuresIntro />
  <MissablesIntro />

  <div class="sticky top-0 z-10 col-span-2">
    <Divider label="Disk 1" />
  </div>

  <TreasuresDisk1 />
  <MissablesDisk1 />

  <div class="sticky top-0 z-10 col-span-2">
    <Divider label="Disk 2" />
  </div>

  <TreasuresDisk2 />
  <MissablesDisk2 />

  <div class="sticky top-0 z-10 col-span-2">
    <Divider label="Disk 3" />
  </div>

  <TreasuresDisk3 />
  <MissablesDisk3 />

  <div class="sticky top-0 z-10 col-span-2">
    <Divider label="Disk 4" />
  </div>

  <TreasuresDisk4 />
  <MissablesDisk4 />
</div>

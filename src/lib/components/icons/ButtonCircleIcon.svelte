<script lang="ts">
  import CircleCircle from '~icons/pepicons-print/circle-circle';
  import clsx from 'clsx';

  const { className }: { className?: string } = $props();
</script>

<CircleCircle class={clsx('text-playstation-circle', className)} />

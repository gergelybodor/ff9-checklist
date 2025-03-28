<script lang="ts">
  import SquareCircle from '~icons/pepicons-print/square-circle';
  import clsx from 'clsx';

  const { className }: { className?: string } = $props();
</script>

<SquareCircle class={clsx('text-playstation-square', className)} />

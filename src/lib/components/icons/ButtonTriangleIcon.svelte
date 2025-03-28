<script lang="ts">
  import TriangleUpCircle from '~icons/pepicons-print/triangle-up-circle';
  import clsx from 'clsx';

  const { className }: { className?: string } = $props();
</script>

<TriangleUpCircle class={clsx('text-playstation-triangle', className)} />

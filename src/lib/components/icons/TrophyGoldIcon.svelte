<script lang="ts">
  import Trophy from '~icons/pepicons-print/trophy';
  import clsx from 'clsx';

  const { className }: { className?: string } = $props();
</script>

<Trophy class={clsx('text-trophy-gold', className)} />

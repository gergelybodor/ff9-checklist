<script lang="ts">
  import TimesCircle from '~icons/pepicons-print/times-circle';
  import clsx from 'clsx';

  const { className }: { className?: string } = $props();
</script>

<TimesCircle class={clsx('text-playstation-cross', className)} />

<script>
	import '../app.css';
  import ThemeSwitch from '$lib/ThemeSwitch/ThemeSwitch.svelte';
</script>

<div class="font-dmsans w-auto min-h-screen bg-sky-100 text-sky-950 dark:bg-darkBlue dark:text-sky-100">
	<ThemeSwitch />
  <slot />
</div>

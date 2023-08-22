<script>
	import '../app.css';
  import ThemeSwitch from '$lib/ThemeSwitch/ThemeSwitch.svelte';
</script>

<div class="w-auto min-h-screen bg-sky-100 text-sky-950 dark:bg-sky-950 dark:text-sky-100">
	<ThemeSwitch />
  <slot />
</div>

<script>
	import '../app.css';
  import ThemeSwitch from '$lib/ThemeSwitch/ThemeSwitch.svelte';
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<div class="font-dmsans w-auto h-fit bg-sky-100 text-sky-950 dark:bg-darkBlue dark:text-sky-100">
  <main class="container mx-auto flex flex-col h-screen">
    <Header />
    <slot />
    <Footer />
  </main>
</div>

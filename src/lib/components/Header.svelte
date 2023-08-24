<script>
	import ThemeSwitch from "$lib/ThemeSwitch/ThemeSwitch.svelte";

</script>

<header class="flex flex-col md:flex-row items-center justify-around md:justify-between px-8 text-center h-40 md:h-20 overflow-hidden">
  <!-- Logo -->
  <div class="md:mt-7 bg-logo-light-mode dark:bg-logo-dark-mode bg-no-repeat h-20 w-48 mx-auto md:mx-0 object-center"></div>

  <div class="flex-col md:flex-row items-center justify-center space-x-4 md:space-x-10 md:absolute">
    <a href="#features" class="hover:text-accentCyan">Features</a>
    <a href="#testimonials" class="hover:text-accentCyan">Testimonials</a>
  </div>

  <ThemeSwitch />
</header>


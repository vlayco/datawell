<script>
	import ThemeSwitch from "$lib/ThemeSwitch/ThemeSwitch.svelte";

</script>

<header class="flex flex-col md:flex-row items-center justify-around md:justify-between space-y-1 px-8 text-center h-44 md:h-24 overflow-hidden w-full">
  <!-- Logo -->
  <div class="mt-4 md:mt-7 bg-logo-light-mode dark:bg-logo-dark-mode bg-no-repeat h-20 w-44 mx-auto md:mx-0"></div>

  <div class="flex flex-col md:flex-row items-center justify-center space-x-4 md:space-x-10 space-y-2 md:space-y-0">
    <a href="#features" class="hover:text-accentCyan">Features</a>
    <a href="#testimonials" class="hover:text-accentCyan">Testimonials</a>

    <!-- Todo: fancy up the theme toggle UI -->
    <ThemeSwitch />
  </div>

</header>


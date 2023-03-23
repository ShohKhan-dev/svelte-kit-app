<script lang="ts">
	import Footer from "$lib/Footer.svelte";
	import Header from "$lib/Header.svelte";
  </script>
  
  <div class="app">
	<Header />
  
	<main>
	  <slot />
	</main>
  
	<Footer />
  </div>
  
  <style>

  </style>
<script>
  import { DarkMode, Navbar, NavBrand, NavLi, NavUl, NavHamburger, TextPlaceholder, Card, Button } from 'flowbite-svelte';
  import { page } from '$app/stores';
</script>
<div class="flex items-center hidden">
  <DarkMode/>
</div>


<br><br><br>

<div class="container mx-auto">
    <div class="text-gray-600 dark:bg-slate-800 bg-white shadow-md text-center rounded-lg p-4">
      <h5 class="text-gray-600 text-xl font-semibold mb-2 dark:text-white">{$page.status}: {$page.error.message}</h5>
      <p class="text-gray-600 dark:text-slate-400">Someone thought this page was a cookie. They ate it all up :)</p>
	</div>
</div>



<style>
	ul {
	  display: block;
	  list-style-type: disc;
	  margin-top: 1em;
	  margin-bottom: 1 em;
	  margin-left: 0;
	  margin-right: 0;
	  padding-left: 40px;
	}
	.listelement:hover {
	  text-decoration: underline;
	}
</style>
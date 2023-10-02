<script>
  import { DarkMode, Navbar, NavBrand, NavLi, NavUl, NavHamburger, TextPlaceholder, Card, Button } from 'flowbite-svelte';
	export let page;
	let isHomePage = page === "home";
</script>


<div class="relative px-8">
  <Navbar navClass="px-2 sm:px-4 py-2.5 absolute w-full z-20 top-0 right-0 border-b" let:hidden let:toggle>
    <div class="flex items-center justify-between w-full">
      <div class="flex items-center space-x-4">
        <NavBrand href="/">
          <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Owen's Projects</span>
        </NavBrand>
        <NavHamburger on:click={toggle} />
      </div>
      <div class="flex items-center">
		<NavUl {hidden}>
			<NavLi href="/" active={true}>Home</NavLi>
        </NavUl>
        <DarkMode/>
      </div>
    </div>
  </Navbar>
</div>
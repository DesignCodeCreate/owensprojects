<script>
  import { DarkMode, Navbar, NavBrand, NavLi, NavUl, NavHamburger, TextPlaceholder, Card, Button } from 'flowbite-svelte';
</script>


<div class="relative px-8">
  <Navbar navClass="px-2 sm:px-4 py-2.5 absolute w-full z-20 top-0 right-0 border-b" let:hidden let:toggle>
    <div class="flex items-center justify-between w-full">
      <div class="flex items-center space-x-4">
    <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Owen's Projects</span>
      </div>
      <div class="flex items-center">
        <DarkMode/>
      </div>
    </div>
  </Navbar>
</div>
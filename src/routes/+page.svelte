<script>
	import Navbar from "../components/NavbarMod.svelte";
</script>

<Navbar></Navbar>

<br><br><br>

<div class="container mx-auto mt-8">
    <div class="text-gray-600 dark:bg-slate-800 bg-white shadow-md rounded-lg p-4 mb-4">
      <h5 class="text-gray-600 text-xl font-semibold mb-2 dark:text-white">Welcome to Owen's Projects!</h5>
      <p class="text-gray-600 dark:text-slate-400">Hello, I'm from the UK, and I'm a developer with a passion for creating cool projects. I specialize in software development.</p>
		<br>
		<p class="text-gray-600 dark:text-slate-400">Some of my other hobbies include: </p>
			<ul class="dark:text-slate-400 text-gray-600" style="list-style-type:circle">
				<li>Gaming</li>
				<li>Electronics</li>
				<li>CAD (Computer Aided Design)</li>
				<li>3D modelling in <a class="listelement" href="https://blender.org" target="_blank"><b>blender</b></li>
			</ul>
		<br>
		<p class="text-gray-600 dark:text-slate-400">Online, I am known as DesignCodeCreate.</p>
    </div>
</div>

<div class="container mx-auto mt-8">
    <div class="text-gray-600 dark:bg-slate-800 bg-white shadow-md rounded-lg p-4 mb-4">
      <h5 class="text-gray-600 text-xl font-semibold mb-2 dark:text-white">Aquachat</h5>
      <p class="text-gray-600 dark:text-slate-400">A basic matrix client with very few features, and this project is on hold.</p>
		<p class="text-gray-600 dark:text-slate-400">You can check it out for yourself with
			<a class="listelement" href="https://aquachat.owensprojects.com" target="_blank"><b>this link</b></a>.</p>
		<br>
		<h5 class="text-gray-600 text-l font-semibold mb-2 dark:text-white">Features</h5>
		<ul class="dark:text-slate-400 text-gray-600" style="list-style-type:circle">
			<li>A very basic login system with SSO support</li>
			<li>Light and dark theme</li>
			<li>Message viewing and typing events</li>
			<li>Very basic room management</li>
			<li>User presence and listing</li>
		</ul>
		<br>
		<p class="text-gray-600 dark:text-slate-400">I plan to rewrite this in the future using the matrix rust sdk and wasm.</p>

	</div>
</div>

<div class="container mx-auto mt-8">
    <div class="text-gray-600 dark:bg-slate-800 bg-white shadow-md rounded-lg p-4 mb-4">
		<h5 class="text-gray-600 text-xl font-semibold mb-2 dark:text-white">Links</h5>
		<ul class="dark:text-slate-400 text-gray-600" style="list-style-type:circle">
			<li class="listelement"><a href="https://github.com/DesignCodeCreate" target="_blank"><b>GitHub</b></li>
			<li class="listelement"><a href="https://discord.com/users/934133252397076540" target="_blank"><b>Discord</b></li>
			<li class="listelement"><a href="https://namemc.com/profile/DesignCodeCreate" target="_blank"><b>Minecraft</b></li>
		</ul>
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
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
				<li>Reading</li>
				<li>CAD (Computer Aided Design)</li>
			</ul>
		<br>
		<p class="text-gray-600 dark:text-slate-400">Online, I am known as DesigningCodingCreating or DesignCodeCreate.</p>
    </div>
</div>

<div class="container mx-auto mt-8">
    <div class="text-gray-600 dark:bg-slate-800 bg-white shadow-md rounded-lg p-4 mb-4">
      <h5 class="text-gray-600 text-xl font-semibold mb-2 dark:text-white">OwenTheBot</h5>
      <p class="text-gray-600 dark:text-slate-400">I've made a Discord bot that does some cool stuff.</p>
		<p class="text-gray-600 dark:text-slate-400">You can see the bot's commands and functions with
  <a class="listelement" href="https://owenthebot.owensprojects.com" target="_blank"><b>this link</b></a>.</p>
		<br>
		<p class="text-gray-600 dark:text-slate-400">You can invite the bot to your Discord server <a class="listelement" href="https://discord.com/api/oauth2/authorize?client_id=973939317900734555&permissions=139586948160&scope=applications.commands%20bot" target="_blank"><b>here</b></a>.</p>
    </div>
</div>

<div class="container mx-auto mt-8">
    <div class="text-gray-600 dark:bg-slate-800 bg-white shadow-md rounded-lg p-4 mb-4">
      <h5 class="text-gray-600 text-xl font-semibold mb-2 dark:text-white">FishyGames</h5>
      <p class="text-gray-600 dark:text-slate-400"></p>
		<p class="text-gray-600 dark:text-slate-400">This is a basic games website made with Svelte and TailwindCSS.</p>
		<br>
		<p class="text-gray-600 dark:text-slate-400">You can visit the website <a class="listelement" href="https://fishygames.owensprojects.com" target="_blank"><b>here</b></a>.</p>
    </div>
</div>


<div class="container mx-auto mt-8">
    <div class="text-gray-600 dark:bg-slate-800 bg-white shadow-md rounded-lg p-4 mb-4">
		<h5 class="text-gray-600 text-xl font-semibold mb-2 dark:text-white">Some Links</h5>
		<ul class="dark:text-slate-400 text-gray-600" style="list-style-type:circle">
			<li class="listelement"><a href="https://github.com/DesigningCodingCreating" target="_blank"><b>GitHub</b> - DesigningCodingCreating</a></li>
			<li class="listelement"><a href="https://discord.com/users/934133252397076540" target="_blank"><b>Discord</b> - DesigningCodingCreating</a></li>
			<li class="listelement"><a href="https://namemc.com/profile/DesignCodeCreate" target="_blank"><b>Minecraft</b> - DesignCodeCreate</a></li>
			<li class="listelement"><a href="https://replit.com/@DesigningCodingCreating" target="_blank"><b>Replit</b> - DesigningCodingCreating</a></li>
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
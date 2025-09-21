<script>
	import Typewriter from 'svelte-typewriter';
</script>

<div class="@container flex flex-col min-h-screen my-2 min-w-full" id="content">
	<Typewriter mode="cascade" cursor={false}>
	<header class="text-center">
		<h1 class="mt-5"><span class="text-4xl md:text-5xl text-cyan-400">Support for WWF</span></h1>
		<h2 class="mt-5"><span class="text-3xl md:text-4xl text-cyan-400">This website is about what the WWF does and how we can support</span></h2>
	</header>
	</Typewriter>
</div>

<style>
	#content {
		background-image: url('/images/panda-bg.webp');
		background-repeat: no-repeat;
		background-size: 100vh 100vw;
		background-attachment: fixed;
		background-position: center;
	}
</style>
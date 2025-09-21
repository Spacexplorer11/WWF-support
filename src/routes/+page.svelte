<script>
	import Typewriter from "svelte-typewriter";
</script>

<div class="@container my-2 flex min-h-screen min-w-full flex-col" id="content">
	<Typewriter mode="cascade" cursor={false}>
		<header class="text-center">
			<h1 class="mt-5"><span class="text-4xl text-green md:text-5xl">Support for WWF</span></h1>
			<h2 class="mt-5">
				<span class="rounded-xl bg-white/50 px-2 text-3xl text-light-blue md:text-4xl"
					>This website is about what the WWF does and how we can support</span
				>
			</h2>
		</header>
	</Typewriter>
</div>

<style>
	#content {
		background-image: url("/images/panda-bg.webp");
		background-repeat: no-repeat;
		background-size: 100vh auto;
		background-attachment: fixed;
		background-position: center;
	}
</style>

<script>
	import Typewriter from "svelte-typewriter";
	import { goto } from "$app/navigation";
</script>

<div class="@container my-2 flex min-h-screen min-w-full flex-col">
	<Typewriter mode="cascade" cursor={false}>
		<header class="text-center">
			<h1 class="mt-5 text-4xl text-green md:text-5xl">Support for WWF</h1>
			<h2 class="mt-5">
				<span class="rounded-xl bg-[#bcd8c1]/90 px-2 text-3xl text-light-blue md:text-4xl"
					>This website is about what the WWF does and how we can support</span
				>
			</h2>
		</header>
		<div class="@container/buttons flex w-full flex-row">
			<button
				onclick={goto("/WWF-work")}
				class="m-2 w-1/2 rounded-xl bg-green/80 p-2 text-2xl text-dark-blue hover:bg-green/100 md:text-3xl"
			>
				What the WWF does
			</button>
			<button onclick="{goto('/WWF-support')}" class="m-2 w-1/2 rounded-xl bg-green/80 p-2 text-2xl text-dark-blue hover:bg-green/100 md:text-3xl">
				How we can support
			</button>
			-->
		</div>
	</Typewriter>
</div>

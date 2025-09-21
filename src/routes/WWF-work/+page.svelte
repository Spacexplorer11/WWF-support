<script>
	import Typewriter from "svelte-typewriter";
</script>

<div class="@container my-2 flex min-h-screen min-w-full flex-col text-center" id="content">
	<Typewriter mode="cascade" cursor={false}>
		<header>
			<h1 class="mt-5"><span class="text-4xl text-green md:text-5xl">What the WWF does</span></h1>
		</header>
		<main class="my-2 space-y-2 text-dark-blue">
			<p class="text-2xl md:text-3xl">
				<span class="rounded-xl bg-[#bcd8c1]/80 px-2">
					The WWF does a lot of things to support wildlife across the planet. Their work is crucial
					to the survival of everyone, including humans.
				</span>
			</p>
			<h3 class="text-3xl text-green md:text-4xl">
				<span class="rounded-xl bg-[#bcd8c1]/80 px-2">How?</span>
			</h3>
			<p class="text-2xl md:text-3xl">
				<span class="rounded-xl bg-[#bcd8c1]/80 px-2"
					>Well without animals, the food chain would fail, and humans, plants, everything would
					fall out of balance.</span
				>
			</p>
			<p class="text-2xl md:text-3xl">
				<span class="rounded-xl bg-[#bcd8c1]/80 px-2"
					><em>Equilibrim</em> is <strong>extremely</strong> important</span
				>
			</p>
			<p class="text-2xl md:text-3xl">
				<span class="rounded-xl bg-[#bcd8c1]/80 px-2"
					>The <strong>World Wildlife Fund</strong> does a lot of work to
					<em>"bring the world back to life"</em> such as working with local people, governments and
					communities.</span
				>
			</p>
			<p class="text-2xl md:text-3xl">
				<span class="rounded-xl bg-[#bcd8c1]/80 px-2"
					>One example of what they did is stop the establishment of <a
						href="https://www.wwf.org.uk/success-stories/megafarm-win"
						class="text-dark-blue underline"><em>"Megafarms"</em> in Norfolk</a
					></span
				>
			</p>
		</main>
	</Typewriter>
</div>

<script>
	import "../app.css";
	import favicon from "$lib/assets/favicon.svg";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div id="bg">
{@render children?.()}
</div>
	<style>
		#bg {
			background-image: url("/images/panda-bg.webp");
			background-repeat: no-repeat;
			background-size: 100vh auto;
			background-attachment: fixed;
			background-position: center;
		}
	</style>

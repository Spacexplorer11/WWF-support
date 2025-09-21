<script>
	import "../app.css";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" type="image/png" href="/favicons/favicon-96x96.png" sizes="96x96" />
	<link rel="icon" type="image/svg+xml" href="/favicons/favicon.svg" />
	<link rel="shortcut icon" href="/favicons/favicon.ico" />
	<link rel="apple-touch-icon" sizes="180x180" href="/favicons/apple-touch-icon.png" />
	<link rel="manifest" href="/favicons/site.webmanifest" />
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

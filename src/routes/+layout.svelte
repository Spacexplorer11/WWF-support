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
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?family=National+Park:wght@200..800&display=swap"
		rel="stylesheet"
	/>
	<title>WWF Support</title>
</svelte:head>

<div class="national-park">
	{@render children?.()}
</div>

<style>
	.national-park {
		font-family: "National Park", sans-serif;
		font-optical-sizing: auto;
		font-weight: 600;
		font-style: normal;
	}
</style>

<script>
	import { House } from "@lucide/svelte";
	import { goto } from "$app/navigation";

	let { children } = $props();
</script>

<button onclick={goto("/")} class="max-w-fit cursor-pointer">
	<House class="mx-2 my-2" color="#007991" />
</button>
{@render children?.()}

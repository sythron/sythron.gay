<script lang="ts">
	import favicon from "$lib/assets/favicon.svg";
	import { title } from "node:process";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>Syth</title>
</svelte:head>

{@render children()}

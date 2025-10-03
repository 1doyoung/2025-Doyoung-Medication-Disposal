<script>
	import '../app.css';
	import Nav from "../components/nav.svelte"
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>


<Nav />

{@render children?.()}
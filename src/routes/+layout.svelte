<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/fud.png';
	import '@fontsource/pixelify-sans/400.css';
	import '@fontsource/geist-mono/400.css';
	import '@fontsource/geist-mono/700.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<link rel="canonical" href="https://fud.team/" />
	<meta property="og:title" content="team fud - we make comp tools sometimes!" />
	<meta property="og:url" content="https://fud.team/" />
	<meta
		property="og:description"
		content="dumb tools for smart people and smart tools for dumb people."
	/>
	<meta property="og:image" content={favicon} />
	<title>team fud :)</title>
	<meta name="description" content="dumb tools for smart things" />
</svelte:head>
{@render children()}

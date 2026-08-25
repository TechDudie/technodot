<script lang="ts">
	import '@fontsource/jetbrains-mono';
	import '@sarap422/font-d-din/font-face.adjusted.css';
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
{@render children()}

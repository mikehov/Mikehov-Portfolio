<script>
	import Header from '$lib/Header/Header.svelte';
	import Footer from '$lib/Footer/Footer.svelte';
	import '../app.css';
	import { onMount } from 'svelte';
		onMount(()=>{AOS.init();})
</script>

<svelte:head>
	<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
	<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
</svelte:head>

<Header></Header>

<main>
	<slot />
</main>

<Footer></Footer>

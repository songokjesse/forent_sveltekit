<script>
	import Navbar from '../component/navbar.svelte';
</script>

<svelte:head>
	<title>Learn Svelte</title>
	<style>
		body {
			font-family: 'Nunito', sans-serif;
		}
	</style>
</svelte:head>

<!-- <Navbar></Navbar> -->

<div class="container">
	<slot />
</div>

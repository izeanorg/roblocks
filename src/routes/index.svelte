<script context="module">
	export const prerender = true;
</script>

<script>
	import Counter from '$lib/Counter.svelte'
	import Login from '$lib/Login.svelte';
</script>

<svelte:head>
	<title>Home - Login/Sign Up</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
<img src="src/lib/header/roblocks-logo.svg" width=200 height=auto/>
<h3>a Flex bot</h3>
<Login />
</section>
<section>
<h2>HOW IT WORKS ></h2>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}


	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>

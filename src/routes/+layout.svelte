<script>
	import { onMount } from 'svelte';
	import { themeChange } from 'theme-change';
	import '../app.css';
	import Header from '$lib/components/Header.svelte';

	onMount(() => {
		themeChange(false);
	});
</script>

<div class="app" data-theme="lofi">
	<Header />

	<main>
		<slot />
	</main>

	<footer>
		<p>Copywrite Richard Schineller <a href="mailto:rjs@rjsiii.com">rjsiii.com</a> © 2022</p>
	</footer>
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>

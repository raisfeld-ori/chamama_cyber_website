<script>
    import Navbar from './Navbar.svelte';
	import './styles.css';
</script>

<div class="app">
	<Navbar items={{'test item': '#', 'something': '#'}}/>
	<main>
		<slot />
	</main>

	<footer>
	</footer>
</div>
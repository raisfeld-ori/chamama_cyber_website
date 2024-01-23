<script>
    import Navbar from './Navbar.svelte';
	import './styles.css';
	import logo from '$lib/images/chamama.png';
</script>

<div class="app">
	<img class="new_background" src={logo} style="display: none;" alt="">
	<div class="fadeIn" style="line-height: 1svh;">
	<a href="https://www.chamama.org" target="_blank" class="hamama-phone"><img src={logo} alt="chamama"></a>
	<div class="box" id="colorBox">מרחב להתפתחות אישית ויזמות מקיימת</div>
	<!--items are: 'name': 'url'-->
	<Navbar  items={{'לאתר הראשי': 'https://www.chamama.org', 'תלמידים': 'students', 'למידה': 'learning', 'תוצרים': 'products','עמוד ראשי': '/'}}/>
	</div>
	<main>
		<slot />
	</main>

	<footer>
	</footer>
</div>

<style>

</style>
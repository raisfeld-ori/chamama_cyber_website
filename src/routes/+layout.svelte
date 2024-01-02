<script>
    import Navbar from './Navbar.svelte';
	import './styles.css';
	import logo from '$lib/images/chamama.png';
</script>

<div class="app">
	<img id="new_background" src={logo} style="display: none;" alt="">
	<div class="fadeIn" style="line-height: 1svh;">
	<a href="https://www.chamama.org" target="_blank" class="hamama-phone"><img src={logo} alt="chamama"></a>
	<div class="box" id="colorBox">מרחב להתפתחות אישית ויזמות מקיימת</div>
	<h1 id="head" class="fadeIn">!ברוכים הבאים</h1>
	<p id="head" class="fadeIn">זה הדף למגמת מחשבים וללמידה שבתוכו</p>
	<Navbar  items={{'a': 'b', 'c': 'b'}}/>
	</div>
	<main>
		<slot />
	</main>

	<footer>
	</footer>
</div>
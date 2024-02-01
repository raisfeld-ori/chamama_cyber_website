<script>
    import Navbar from './Navbar.svelte';
	import './styles.css';
	import logo from '$lib/images/chamama.png';
	import discord from '$lib/images/discord.png';


</script>

<div class="app">
	<img class="topright" src={discord}  alt="Meaningful description">
	<img class="logo" src={logo} style="display: none;" alt="">
	<div class="fadeIn" style="line-height: 1svh;">
	<a href="https://www.chamama.org" target="_blank" class="hamama-phone"><img src={logo} alt="chamama"></a>
	<a href="https://discord.gg/6T4eTxgPK9" target="_blank" class="topright"><img src={discord} alt="discord"></a>
	<h1 class="texthead">מגמת ההייטק</h1>
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

.topright{
    position: absolute;
    right: 0;
    top: 0;
    display: block;
    height: 100px;
    width:100px;
    text-indent: -999em;
    text-decoration: none;
	transition: transform 0.3s ease-in-out;
}

.topright:hover img{
    transform: scale(1.2);
}

</style>
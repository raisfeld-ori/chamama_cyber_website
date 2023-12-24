
<script>
import logo from '$lib/images/chamama.png';
import learn from '$lib/images/learning1.png';  
import students from '$lib/images/students.jpeg'; 
import projects from '$lib/images/projects.jpg';
import contact from '$lib/images/contact.jpg';  
</script>

<svelte:head>
	<title>Home</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
</svelte:head>

<section>

</section>

<body class="container">
	<img id="new_background" src={logo} style="display: none;" alt="">
	<div class="fadeIn" style="line-height: 1svh;">
	<a href="https://www.chamama.org" target="_blank" class="hamama-phone"><img src={logo} alt="chamama"></a>
	<div class="box" id="colorBox">מרחב להתפתחות אישית ויזמות מקיימת</div>
	<h1 id="head" class="fadeIn">!ברוכים הבאים</h1>
	<p id="head" class="fadeIn">זה הדף למגמת מחשבים וללמידה שבתוכו</p>
	</div>



<div class="container2 V5AUxf fadeIn delay">
	<div class="text-frame" onclick="transition('new_background', 'images/coding.jpg', 'other_pages/study.html');">
		<h1 class="frame-text">צרו קשר</h1>
		<img src={contact} alt="contact">
	</div>
	<div class="text-frame">
		<h1 class="frame-text">השיגים</h1>
		<img src={projects} alt="projects">
	</div>
	<div class="text-frame" onclick="transition('new_background', 'images/gaming-engine.webp', 'test')">
		<h1 class="frame-text">?איך לומדים</h1>
		<img src={learn} alt="learning">
	</div>
	<div class="text-frame">
		<h1 class="frame-text">התלמידים</h1>
		<img src={students} alt="students">
	</div>
</div>





	<footer id="copyright">
		<div> 09-7884549 | Info@chamama.org - ליצירת קשר | Visit@chamama.org - לביקורים</div>
        <div>תיכון החממה - עמל הוד השרון | חרש 9 הוד השרון | ס.מ 775064</div>
	</footer>
</body>

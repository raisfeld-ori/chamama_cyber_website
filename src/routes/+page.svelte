<script>
import learn from '$lib/images/projects.jpg';  
import students from '$lib/images/students.jpeg'; 
import projects from '$lib/images/ikigai.png';
import contact from '$lib/images/contact.jpg';
import development from '$lib/images/development.png';
</script>

<svelte:head>
	<title>עמוד ראשי</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
</svelte:head>

<section>

</section>

<body class="container">
<div class="container2 V5AUxf fadeIn delay">
	<div class="text-frame">
		<h1 class="frame-text">צרו קשר</h1>
		<img src={contact} alt="contact">
	</div>
	<div class="text-frame">
		<a href="/products" style="text-decoration: none; color: inherit;">
		<h1 class="frame-text">תוצרים</h1>
		<img src={projects} alt="projects">
	</div>
	<div class="text-frame">
		<a href="/learning">
		<h1 class="frame-text">?איך לומדים</h1>
		<img src={learn} alt="learning">
		</a>
	</div>
	<div class="text-frame">
		<a href="/students" style="text-decoration: none; color: inherit;">
			<h1 class="frame-text">התלמידים</h1>
			<img src={students} alt="students">
		</a>
	</div>
</div>

</body>

<style>
a{text-decoration: none; color: inherit;}
</style>
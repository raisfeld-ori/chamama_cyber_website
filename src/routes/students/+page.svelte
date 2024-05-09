<script>
    import learn from '$lib/images/projects.jpg';  
    import students from '$lib/images/students.jpeg'; 
    import projects from '$lib/images/ikigai.png';
    import contact from '$lib/images/contact.jpg';
    import Students from './Students.svelte';  
    import studentimg from '$lib/images/sigmagrindset.jpg';
    import sigma from '$lib/images/daddy.jpeg';
    import topg from '$lib/images/topg.png';
    import ariel from '$lib/images/gojo.jpg';


    import { onMount } from 'svelte';

	let scroll_allowed = false;
    onMount(() => {
      scroll_allowed = true;
    })

</script>
<svelte:head>
	<title>עמוד תלמידים</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
</svelte:head>
<div>
<Students names={["Linkedin - אורי", "Linkedin - אביב", "Linkedin -אריאל", "Github - אשל"]} urls={['https://www.linkedin.com/in/ori-raisfeld-422392264/', 'https://www.linkedin.com/in/aviv-segal-7687812a7/', "https://www.linkedin.com/in/ariel-elkaslasi-1b6769299/", "https://github.com/UnmatchedPerspicacious"]} images={[studentimg, sigma, ariel, topg]} />
</div>


{#if scroll_allowed}
  <style>:root{--scroll: hidden;}</style>
{/if}
<style>





</style>
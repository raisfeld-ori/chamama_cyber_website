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
<h1 class="texthead">Linkedin</h1>
<Students names={["אורייז", "אביב", "איתמר", "אשל"]} urls={['https://www.linkedin.com/in/ori-raisfeld-422392264/', 'https://www.linkedin.com/in/ori-raisfeld-422392264/', "https://www.linkedin.com/in/ariel-elkaslasi-1b6769299/"]} images={[studentimg, sigma, ariel, topg]} />
</div>


{#if scroll_allowed}
  <style>:root{--scroll: hidden;}</style>
{/if}
<style>
  :root{--scroll: scroll;}
    .texthead{
   position: static;
   color: rgb(0, 123, 223);

   clear: both;
}
</style>
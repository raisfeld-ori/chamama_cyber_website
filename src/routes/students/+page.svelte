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



    

</script>
<h1 class="texthead">Linkedin</h1>
<Students names={["אורייז", "אביב", "איתמר", "אשל"]} urls={['https://www.linkedin.com/in/ori-raisfeld-422392264/', "delta", "https://www.linkedin.com/in/ariel-elkaslasi-1b6769299/"]} images={[studentimg, sigma, ariel, topg]} />

<style>
  :root{--scroll: scroll;}
    .texthead{
   position: static;
   color: rgb(0, 123, 223);

   clear: both;
}
</style>
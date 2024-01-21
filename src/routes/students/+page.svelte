<script>
    import learn from '$lib/images/projects.jpg';  
    import students from '$lib/images/students.jpeg'; 
    import projects from '$lib/images/ikigai.png';
    import contact from '$lib/images/contact.jpg';
    import Students from './Students.svelte';  
</script>

<Students names={["אוריי", "אביב", "איתמר"]} urls={['sigma', "delta", "beta"]} images={[students, learn, projects]} />
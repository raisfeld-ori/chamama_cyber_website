<script>
    export let names = [];
    export let images = [];
    export let urls = [];
</script>

<div class="container2 V5AUxf fadeIn delay">
    {#each {length: names.length} as _, i}
        <a href={urls[i]}>
        <h1>{names[i]}</h1>
        <img src={images[i]}>
        </a>
    {/each}
</div>
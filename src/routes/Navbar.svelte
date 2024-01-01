<script>
    export let items = {};
</script>

<nav class="navbar">
    {#each Object.entries(items) as [item, url]}
        <a href={url}>{item}</a>
    {/each}
</nav>

<style>
    .navbar{
        display: flex;
        justify-content:left;
        align-items: center;
        background-color: #3a3933;
        height: 3vh;
        position:fixed;
        width:100%;
    }
    .navbar a {
        color: white;
        text-decoration: none;
        text-align: center;
        padding: 10px 10px;
        
    }
</style>

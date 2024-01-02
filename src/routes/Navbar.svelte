<script>
    import { page } from '$app/stores';
    export let items = {};
</script>

<nav class="navbar">
    {#each Object.entries(items) as [item, url]}
        <a href={url} aria-current={page.current}>{item}</a>
    {/each}
</nav>


<style>
      .navbar {
          overflow: hidden;
          background-color: #1c6ee8;
          border-radius: 10px;
          width: 50%;
          height: 2000%;
          margin: 0 auto;
      }

      .navbar a {
          float: left;
          display: block;
          color: #f2f2f2;
          text-align: center;
          padding: 14px 16px;
          text-decoration: none;
      }

      .navbar a:hover {
          color: var(--background);
      }
</style>
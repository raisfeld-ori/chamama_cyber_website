<script>
    import { page } from '$app/stores';
    export let items = {};
 </script>
 
 <nav class="navbar">
    {#each Object.entries(items) as [item, url]}
     <a href={url} aria-current={$page.url.pathname.startsWith('/' + url) || $page.url.pathname == url ? 'page' : ''}>{item}</a>
    {/each}
 </nav>
 
 <style>
 .navbar {
   display: flex;
   justify-content: center;
   flex-wrap: wrap;
   overflow: hidden;
   background-color: #1c6ee8;
   border-radius: 10px;
   width: 60%;
   margin: 10px auto;
 }
 
 .navbar a[aria-current="page"] {
  color: rgba(255, 251, 0, 0.877);
 }
 
 .navbar a {
   display: block;
   color: #f2f2f2;
   text-align: center;
   padding: 14px 16px;
   text-decoration: none;
 }
 
 .navbar a:hover {
   color: var(--background);
 }


 
 /*if the screen is too small, increase the size of the navbar*/
 @media screen and (max-width: 800){.navbar {width: 80%;}}
 
 </style>
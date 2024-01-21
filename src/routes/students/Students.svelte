<script>
    export let names = [];
    export let images = [];
    export let urls = [];
</script>

<div class="container2 V5AUxf fadeIn delay">
    {#each {length: names.length} as _, i}
    <div class="text-frame">
		<a href={urls[i]} style="text-decoration: none; color: inherit;">
			<h1 class="frame-text">{names[i]}</h1>
			<img src={images[i]} alt="" />
		</a>
	</div>
    {/each}
</div>
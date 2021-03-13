<script>
	let secodName = 'Svelte test';
	let srcSvelte = 'https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Svelte_Logo.svg/1200px-Svelte_Logo.svg.png';
</script>

<style lang="scss">
	.main-img{
		width: 30%;
	}
</style>


<img src="{srcSvelte}" class="main-img" />
<h2 class=" mb-0">{secodName}</h2>


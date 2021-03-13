<script>
	export let name;
	import TestComponentList  from './TestComponentList.svelte';
	import TestSearch from './TestSearch.svelte';
	let search = '!!!Search Term!!!';
</script>

<style global lang="scss">
	$color: red;
	$danger: gray;

	@import '../node_modules/bootstrap/scss/bootstrap.scss';

	h1 {
		p{
			font-size: xx-large;
			color: $warning;
		}

		span{
			color: $danger;
		};
		color: $primary;
	}

	.main-img{
		width: 30%;
	}


</style>

<div class="container">
	<h1><p>Hello </p>{name} <span>!</span></h1>
	<p class="text-danger">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
	<TestSearch {search} />
	<TestComponentList />
</div>


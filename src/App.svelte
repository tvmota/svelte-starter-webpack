<script>
	import Icon from './Icon.svelte';
	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
	.teste {
		height: 20px;
		width: 100%;
	}
</style>

<h1>Hello {name}!</h1>
<div class="teste bg-black"></div>
<Icon iconName="web" />

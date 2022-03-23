<svelte:options tag="svelte-wc" />

<script>
	export let name = 'world';
</script>

<h1>Hello {name}!</h1>
<slot></slot>

<style>
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		h1 {
            color: #ff6600;
		}
	}
</style>
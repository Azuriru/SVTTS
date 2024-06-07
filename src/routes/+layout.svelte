<script lang="ts">
    import '../app.css';
</script>

<svelte:head>
    <title>Home</title>
    <meta name="description" content="Sveltekit + Tailwind boilerplate" />
</svelte:head>

<div class="app">
    <slot />
</div>

<style lang="scss">
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}
</style>
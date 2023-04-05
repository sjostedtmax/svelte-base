<script>
	import Hand from '../components/hand.svelte';
</script>

<svelte:head>
	<title>svelte base</title>
</svelte:head>

<div class="main-view">
	<Hand />
</div>

<style lang="scss">
	.main-view {
		z-index: 0;
		width: 100vw;
		height: 100vh;
		background: #21201f;
		display: flex;
		user-select: none;
	}
</style>

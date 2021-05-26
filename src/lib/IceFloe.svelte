<script>
	import Penguin from './Penguin.svelte';

	export let url;
	export let numberOfPenguins;
</script>

<a href={url}>
	<div class="iceFloeContainer">
		{#each Array(numberOfPenguins) as _, i}
			<Penguin />
		{/each}
	</div>
	<img src="/eisscholle1.png" />
</a>

<style>
	.iceFloeContainer {
		display: flex;
		flex-direction: row;
	}
</style>

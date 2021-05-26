<script>
	import '../app.css';
</script>

<div class="appContainer">
	<main>
		<slot />
	</main>
</div>

<style>
	.appContainer {
		width: 100vw;
		height: 100vh;
		background-image: url('background.png');
	}
</style>

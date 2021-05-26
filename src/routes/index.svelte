<script>
	import IceFloe from '$lib/IceFloe.svelte';
</script>

<div class="indexContainer">
	<div class="one scholle">
		<IceFloe url="one" />
	</div>
	<div class="two scholle">
		<IceFloe url="two" />
	</div>
	<div class="three scholle">
		<IceFloe url="three" />
	</div>
	<div class="four scholle">
		<IceFloe url="four" />
	</div>
	<div class="five scholle">
		<IceFloe url="five" />
	</div>
	<div class="six scholle">
		<IceFloe url="six" />
	</div>
	<div class="seven scholle">
		<IceFloe url="seven" />
	</div>
</div>

<style>
	.indexContainer {
		width: 100%;
		height: 100%;
	}

	.scholle {
		position: fixed;
	}
	.one {
		width: 300px;
		height: 100px;
		bottom: 30%;
		left: 3%;
	}
	.two {
		width: 350px;
		height: 100px;
		bottom: 20%;
		left: 18%;
	}
	.three {
		width: 300px;
		height: 80px;
		bottom: 5%;
		left: 10%;
	}
	.four {
		width: 300px;
		height: 80px;
		bottom: 10%;
		left: 30%;
	}
	.five {
		width: 300px;
		height: 80px;
		bottom: 28%;
		left: 45%;
	}
	.six {
		width: 300px;
		height: 100px;
		bottom: 1%;
		left: 60%;
	}
	.seven {
		width: 300px;
		height: 80px;
		bottom: 30%;
		left: 80%;
	}
</style>

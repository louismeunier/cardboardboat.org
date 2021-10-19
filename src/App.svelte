<script>
	import { fade } from "svelte/transition";
	import Boat from "./components/Boat.svelte";
import Idea from "./components/Idea.svelte";
import Math from "./components/Math.svelte";
</script>

<style>
	main {
		display: grid;
		grid-auto-flow: row;
		grid-template-rows: 1fr auto auto;
		align-items: center;
		font-family: "Apple Garamond";
		/* background: linear-gradient(var(--silver), var(--dark-gray)); */
	}

	main div {
		width: 100%;
	}

	.wrapper {
		display: grid;
		gap: 2em;
		text-align: center;
		place-items: center;
		height: 100vh;
	}

	.subwrapper {
		height: min-content;
		width: 100%;
		display: grid;
		justify-content: center;
		justify-items: center;
		grid-auto-flow: row;
		padding: 1em;
		gap: 2em;
	}
</style>

<main>
	<div class="wrapper">
		<div class="subwrapper">
			<h1 class="title">boat.</h1>
			<Boat/>
			<i>"Because all great things start in a garage."</i>
			<span class="credit">~ John Smith, 2021</span>
		</div>
	</div>
	<Idea/>
	<Math/>
</main>
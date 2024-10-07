<script>
	import Spacer from "$lib/Spacer.svelte";
</script>

<h1>Past seasons</h1>
<div id="seasons-container">
	<div class="season">
		<h2>2023: Namazu</h2>
		<iframe
			src="https://www.youtube.com/embed/MWyBbpCCDfY?si=qAUkpqkidtWxNgsH"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			allowfullscreen
		/>
		<p>Namazu was our 2023 robot for the game Charged Up. His objective was to place cones and cubes on a grid.</p>
	</div>
	<br>
	<br>
	<div class="season">
		<h2>2024: Ruamoko</h2>
		<iframe
			src="https://www.youtube.com/embed/wysQTf0XY6I"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			allowfullscreen
		/>
		<p>Raumoko was our 2024 robot for the game Crescendo. His objective was to shoot oragne discs, called notes, into an amp. </p>
	</div>
</div>
<Spacer />

<style>
	#seasons-container {
		display: flex;
		width: 100%;
		align-items: center;
		justify-content: center;
		flex-direction: column;
	}
	.season {
		background-color: var(--primary);
		color: white;
		width: min-content;
		padding-left: 5vw;
		padding-right: 5vw;
		border-radius: 1vw;
	}
	iframe {
		width: 60vw;
		aspect-ratio: 16/9;
	}
</style>

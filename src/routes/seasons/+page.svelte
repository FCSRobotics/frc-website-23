<script> 
	import Spacer from "$lib/Spacer.svelte";
</script>

<h1>Past seasons</h1> <!--GIVE EACH OWN PAGE--> <!--add real videos-->
<div id="seasons-container">


	<div class="season">
		<h1>2026: Rebuilt</h1>
		<h2>Video</h2>
		<iframe
			src="https://www.youtube.com/watch?v=_fybREErgyM"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			allowfullscreen
		/>
		<p>[tbd] is our robot for the 2026 season, Rebuilt.</p>
	</div>


	<div class="season">
		<h1>2025: Reefscape</h1>
		<h2>Video</h2>
		<iframe
			src="https://www.youtube.com/watch?v=YWbxcjlY9JY"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			allowfullscreen
		/>
		<p>Sif was our robot for the 2025 season, Reefscape.</p>
	</div>


	<div class="season">
		<h1>2024: Crescendo</h1>

		<h2>Video</h2>
		<iframe
			src="https://www.youtube.com/watch?v=vXm6ep3X_aI"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			allowfullscreen
		/>
		<p>Raumoko was our 2024 robot for the game Crescendo. His objective was to shoot oragne discs, called notes, into an amp. </p>
	</div>

	<div class="season">
		<h1>2023: Charged Up</h1>

		<h2>Video</h2>
		<iframe
			src="https://www.youtube.com/watch?v=0zpflsYc4PA"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			allowfullscreen
		/>
		<p>Namazu was our 2023 robot for the game Charged Up. His objective was to place cones and cubes on a grid.</p>
	</div>
	<br>
	<br>
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

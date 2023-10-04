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
		<p>We did some robotics this season</p>
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

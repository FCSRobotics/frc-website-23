<script>
	import Spacer from "$lib/Spacer.svelte";
</script>

<h1>Mentors!</h1>
<div class="team-grid">
	<img src="/people/mscho.jpg" alt="Mr Schoifet" />
</div>
<h1>Students!</h1>
<div class="team-grid">
	<img src="/people/jack.png" alt="Jack" />
	<img src="/people/zubin.jpg" alt="Zubin" />
	<img src="/people/alex.jpg" alt="Alex" />
	<img src="/people/aaron.jpg" alt="Aaron" />
	<img src="/people/andrew.jpg" alt="Andrew" />
	<img src="/people/julia.jpg" alt="Julia" />
	<img src="/people/landon.jpg" alt="Landon" />
	<img src="/people/charlie.jpg" alt="Charlie" />
	<img src="/people/eli.jpg" alt="Eli" />
	<img src="/people/parth.jpg" alt="Parth" />
</div>
<Spacer />

<style>
	.team-grid {
		display: grid;
		grid-template-columns: 1fr 1fr 1fr 1fr;
		width: 80%;
		margin: auto;
		gap: 4vw;
		justify-items: center;
		align-items: center;
	}

	img {
		width: 100%;
		height: 100%;
		border-radius: 30px;
	}
</style>

<script>
	import Person from "$lib/Person.svelte";
	import Spacer from "$lib/Spacer.svelte";
</script>

<h1>Mentors</h1>
<div class="team-grid">
	<Person src="/people/mscho.jpg" name="Matt Schoifet" alt="Mr Schoifet" />
	<Person src="/people/akash.jpeg" name="Akash" alt="Akash" />
	<Person src="/people/ben.jpeg" name="Ben" alt="Ben" />
	<Person src="/people/jose.webp" name="Jose" alt="Jose" />
</div>
<h1>Students</h1>
<div class="team-grid">
	<Person src="/people/paco.jpg" alt="Paco" bio="I play piano." name="Paco" />
	<Person src="/people/jackw.jpg" name="Jack" alt="Jack" />
	<Person src="/people/rishi.jpg" name="Rishi" alt="Rishi" />
	<Person
		src="/people/zubin.jpg"
		name="Zubin"
		bio="I like woodworking, video games (despite my lack of skill), cooking, and most of all, I love planes. I am a total plane nerd."
		alt="Zubin"
	/>
	<Person src="/people/charlie.jpg" name="Charlie" alt="Charlie" />
	<Person src="/people/oliver.jpg" name="Oliver" alt="Oliver" />
	<Person src="/people/julia.jpg" name="Julia" alt="Julia" />
	<Person src="/people/jordanc.jpg" name="Jordan" alt="Jordan" />
	<Person
		src="/people/jack.png"
		name="Jack"
		bio="Captain by day, masked vigilante by night"
		alt="Jack"
	/>
	<Person src="/people/nate.jpg" name="Nate" alt="Nate" />
	<Person
		src="/people/eli.jpg"
		name="Eli"
		bio="Rock Climb Ooga Boga, Large Axe, Scary Death Robot "
		alt="Eli"
	/>
	<Person src="/people/jordan.jpg" name="Jordan" alt="Jordan" />

	<Person src="/people/alex.jpg" name="Alex" alt="Alex" />
	<Person src="/people/aaron.jpg" name="Aaron" alt="Aaron" />
	<Person src="/people/andrew.jpg" name="Andrew" alt="Andrew" />

	<Person src="/people/landon.jpg" name="Landon" alt="Landon" />

	<Person src="/people/parth.jpg" name="Parth" alt="Parth" />
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
</style>

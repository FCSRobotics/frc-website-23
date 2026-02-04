<script> //add photos
  import Person from "$lib/Person.svelte";
  import Spacer from "$lib/Spacer.svelte";
</script>
 
<h1>Mentors</h1>
<div class="team-grid">
  <Person src="/people/mscho.jpg" name="Matthew Leotine Alastair Schoifet IV" alt="Schozus" /> <!--add-->
  <Person src="/people/akash.jpeg" name="Akash" alt="Akash" /> <!--add-->
  <Person src="/people/sharon.jpeg" name="Sharon" alt="Sharon" /> <!--add-->
  <Person src="/people/ben.jpeg" name="Ben" alt="Ben" /> <!--add-->
  <Person src="/people/mike.webp" name="Mike Dillon" alt="Mike Dillon" /> <!--add-->
</div>
<h1>Programming</h1>
<p>(the best team)</p>
<div class="team-grid">
  <Person src="/people/charliegjpeg" name="Charlie Gerbert Hurst" alt="Charlie" /> <!--add-->
  <Person src="/people/sophie.jpg" name="Sophie" alt="Sophie" /> <!--add-->
  <Person src="/people/asa.jpg" name="Asa" alt="Asa" /> <!--add-->
  <Person src="/people/oliver.jpeg" name="Oliver" alt="Oliver" /> <!--add-->

  <Person src="/people/ian.jpeg" alt="Ian" name="Ian" /> <!--add-->
  <Person src="/people/maxam.png" name="Maxam" alt="Maxam" /> 

</div>

<h1>Mechanical</h1>

<div class="team-grid">

  <Person src="/people/miless.jpg" name="Miles" alt="Miles"/> <!--add-->
  <Person src="/people/luna.jpg" name="Luna" alt="Luna"/> <!--add-->
  <Person src="/people/julia.jpg" name="Julia" alt="Julia"/> <!--add-->
  <Person src="/people/landon.jpg" name="Landon" alt="Landon" /> <!--add-->

  <Person src="/people/violet.jpg" name="Violet" alt="Violet"/> <!--add-->
  <Person src="/people/parth.jpg" name="Parth" alt="Parth"/> <!--add-->
  <Person src="/people/milesm.jpg" name="Miles" alt="Miles"/> <!--add-->
  <Person src="/people/jackw.jpg" name="Jack" alt="Jack" /> <!--add-->

  <Person src="/people/peter.jpg" name="Peter" alt="Peter"/> <!--add-->
  <Person src="/people/lucy.jpg" name="Lucy" alt="Lucy" /> <!--add-->
  <Person src="/people/clem.png" name="Clementine" alt="Clementine"/> <!--add-->
  <Person src="/people/oona.jpg" name="Oona" alt="Oona" /> <!--add-->

  <Person src="/people/charlieN.jpg" name="Charlie" alt="Charlie"/> <!--add-->
  <Person src="/people/bennett.jpg" name="Bennett" alt="Bennett"/> <!--add-->
  <Person src="/people/arda.jpg" name="Arda" alt="Arda" /> <!--add-->
  <Person src="/people/elliot.jpg" name="Elliot" alt="Elliot"/> <!--add-->

  <Person src="/people/zoya.jpg" name="Zoya" alt="Zoya" /> <!--add-->
  <Person src="/people/ben.jpg" name="Ben" alt="Ben"/> <!--add-->
  <Person src="/people/ezra.jpg" name="Ezra" alt="Ezra"/> <!--add-->
  <Person src="/people/ozzy.jpg" name="Ozzy" alt="Ozzy"/> <!--add-->

</div>

<h1>Field</h1>
<div class="team-grid">
  <Person src="/people/stephen.jpg" name="Stephen" alt="Stephen"/> <!--add-->
  <Person src="/people/felix.jpg" name="Felix" alt="Felix" /> <!--add-->
  <Person src="/people/ryan.jpg" name="Ryan" alt="Ryan" /> <!--add-->
</div>


<h1>Drive Team</h1>
<p>tbd</p>

<div class="team-grid">

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


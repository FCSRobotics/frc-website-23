<script> //add photos
  import Person from "$lib/Person.svelte";
  import Spacer from "$lib/Spacer.svelte";
</script>
 
<h1>Mentors</h1>
<div class="team-grid">
  <Person src="/people/mscho.jpg" name="Matthew Leotine Alastair Schoifet IV" alt="Schozus" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Akash" alt="Akash" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Sharon" alt="Sharon" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Ben" alt="Ben" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Mike Dillon" alt="Mike Dillon" /> <!--add-->
</div>
<h1>Programming</h1>
<p>(the best team)</p>
<div class="team-grid">
  <Person src="/people/mikedillon.jpeg" name="Charlie Gerbert Hurst" alt="Charlie" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Sophie" alt="Sophie" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Asa" alt="Asa" /> <!--add-->
  <Person src="/people/oliver.jpeg" name="Oliver" alt="Oliver" /> <!--add-->

  <Person src="/people/ian.jpeg" alt="Ian" name="Ian" /> <!--add-->
  <Person src="/people/maxam.png" name="Maxam" alt="Maxam" /> 

</div>

<h1>Mechanical</h1>

<div class="team-grid">

  <Person src="/people/mikedillon.jpeg" name="Miles" alt="Miles"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Luna" alt="Luna"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Julia" alt="Julia"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Landon" alt="Landon" /> <!--add-->

  <Person src="/people/mikedillon.jpeg" name="Violet" alt="Violet"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Parth" alt="Parth"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Miles" alt="Miles"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Jack" alt="Jack" /> <!--add-->

  <Person src="/people/mikedillon.jpeg" name="Peter" alt="Peter"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Lucy" alt="Lucy" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Clementine" alt="Clementine"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Oona" alt="Oona" /> <!--add-->

  <Person src="/people/mikedillon.jpeg" name="Charlie" alt="Charlie"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Bennett" alt="Bennett"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Arda" alt="Arda" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Elliot" alt="Elliot"/> <!--add-->

  <Person src="/people/mikedillon.jpeg" name="Zoya" alt="Zoya" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Ben" alt="Ben"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Ezra" alt="Ezra"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Ozzy" alt="Ozzy"/> <!--add-->

</div>

<h1>Field</h1>
<div class="team-grid">
  <Person src="/people/mikedillon.jpeg" name="Stephen" alt="Stephen"/> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Felix" alt="Felix" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Ryan" alt="Ryan" /> <!--add-->
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


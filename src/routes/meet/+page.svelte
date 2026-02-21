<script> //add photos
  import Person from "$lib/Person.svelte";
  import Spacer from "$lib/Spacer.svelte";
</script>
 
<h1>Mentors</h1>
<div class="team-grid">
  <Person src="/people/mscho.jpg" name="Matthew Leotine Alastair Schoifet IV" alt="Schozus" /> <!--add-->
  <Person src="/Gnome_-_Hogwarts_Mystery.webp" name="Akash Shah" alt="Akash Shah" /> <!--add-->
  <Person src="/Gnome_-_Hogwarts_Mystery.webp" name="Sharon" alt="Sharon" /> <!--add-->
  <Person src="/Gnome_-_Hogwarts_Mystery.webp" name="Ben" alt="Ben" /> <!--add-->
  <Person src="/people/mikedillon.jpeg" name="Mike Dillon" alt="Mike Dillon" /> <!--add-->
</div>
<h1>Programming</h1>
<p>(the best team)</p>
<div class="team-grid">
  <Person src="/people/CharlieH.webp" name="Charlie Gerbert Hurst" alt="Charlie" /> <!--add-->
  <Person src="/people/oliver.jpg" name="Oliver" alt="Oliver" /> <!--add-->
  <Person src="/people/Arda.webp" name="Arda" alt="Arda" /> <!--add-->
  <Person src="/people/ian.jpg" alt="Ian" name="Ian" /> <!--add-->

  <Person src="/people/SophieG.webp" name="Sophie" alt="Sophie" /> <!--add-->
  <Person src="/people/AsaS.webp" name="Asa" alt="Asa" /> <!--add-->
  <Person src="/people/maxam.png" name="Maxam" alt="Maxam" /> 

</div>

<h1>Mechanical</h1>

<div class="team-grid">

  <Person src="/people/LunaS.webp" name="Luna" alt="Luna"/> <!--add-->
  <Person src="/people/MilesS.webp" name="Miles" alt="Miles"/> <!--add-->
  <Person src="/people/JuliaB.webp" name="Julia" alt="Julia"/> <!--add-->
  <Person src="/people/LandonC.webp" name="Landon" alt="Landon" /> <!--add-->

  <Person src="/people/VioletK.webp" name="Violet" alt="Violet"/> <!--add-->
  <Person src="/people/JackW.webp" name="Jack" alt="Jack" /> <!--add-->
  <Person src="/people/PeterH.webp" name="Peter" alt="Peter"/> <!--add-->
  <Person src="/people/Lucy.webp" name="Lucy" alt="Lucy" /> <!--add-->

  <Person src="/people/Oona.webp" name="Oona" alt="Oona" /> <!--add-->
  <Person src="/people/StevenN.jpg" name="Steven" alt="Steven"/> <!--add-->
  <Person src="/people/CharlieN.webp" name="Charlie" alt="Charlie"/> <!--add-->
  <Person src="/people/RyanW.webp" name="Ryan" alt="Ryan"/> <!--add-->

  <Person src="/people/BennetM.webp" name="Bennett" alt="Bennett"/> <!--add-->
  <Person src="/people/Elliot.webp" name="Elliot" alt="Elliot"/> <!--add-->
  <Person src="/people/ZoyaT.webp" name="Zoya" alt="Zoya" /> <!--add-->
  <Person src="/people/Benjamin.webp" name="Ben" alt="Ben"/> <!--add-->

  <Person src="/people/EzraS.webp" name="Ezra" alt="Ezra"/> <!--add-->
  <Person src="/people/OzzyL.webp" name="Ozzy" alt="Ozzy"/> <!--add-->

</div>

<h1>Field</h1>
<div class="team-grid">
  <Person src="/people/ClementineL.webp" name="Clementine" alt="Clementine"/> <!--add-->
  <Person src="/people/MilesButBlonde.webp" name="Miles" alt="Miles"/> <!--add-->
  <Person src="/people/FelixL.webp" name="Felix" alt="Felix" /> <!--add-->
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
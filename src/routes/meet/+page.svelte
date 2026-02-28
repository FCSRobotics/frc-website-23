<script> //add photos
  import Person from "$lib/Person.svelte";
  import Spacer from "$lib/Spacer.svelte";
</script>
 
<h1>Mentors</h1>
<div class="team-grid">
  <Person src="/people/mscho.jpg" name="Matthew Schoifet" alt="Schozus" /> 
  <Person src="/people/AkashS.jpeg" name="Akash" alt="Akash Shah" /> <!--add-->
  <Person src="/people/SharonK.jpeg" name="Sharon" alt="Sharon" /> <!--add-->
  <Person src="/people/BenMentor.jpeg" name="Ben" alt="Ben" /> <!--add-->
  <Person src="/people/MikeD.jpeg" name="Mike" alt="Mike" /> 
</div>
<h1>Programming</h1>
<div class="team-grid">
  <Person src="/people/CharlieH.webp" name="Charlie" alt="Charlie" /> 
  <Person src="/people/OliverK.jpg" name="Oliver" alt="Oliver" /> 
  <Person src="/people/Arda.webp" name="Arda" alt="Arda" />
  <Person src="/people/IanJ.jpg" alt="Ian" name="Ian" /> 

  <Person src="/people/SophieG.webp" name="Sophie" alt="Sophie" />
  <Person src="/people/AsaS.webp" name="Asa" alt="Asa" />
  <Person src="/people/MaxamG.png" name="Maxam" alt="Maxam" /> 

</div>

<h1>Mechanical</h1>

<div class="team-grid">

  <Person src="/people/JuliaB.webp" name="Julia" alt="Julia"/>
  <Person src="/people/LandonC.webp" name="Landon" alt="Landon" /> 
  <Person src="/people/JackW.webp" name="Jack" alt="Jack" /> 
  <Person src="/people/PeterH.webp" name="Peter" alt="Peter"/>

  <Person src="/people/MilesS.webp" name="Miles" alt="Miles"/> 
  <Person src="/people/Lucy.webp" name="Lucy" alt="Lucy" /> 
  <Person src="/people/Oona.webp" name="Oona" alt="Oona" /> 
  <Person src="/people/Leila.jpg" name="Leila" alt="Leila" /> 

  <Person src="/people/StevenN.jpg" name="Steven" alt="Steven"/> 
  <Person src="/people/CharlieN.webp" name="Charlie" alt="Charlie"/> 
  <Person src="/people/BennetM.webp" name="Bennett" alt="Bennett"/> 
  <Person src="/people/Elliot.webp" name="Elliot" alt="Elliott"/> 

  <Person src="/people/ZoyaT.webp" name="Zoya" alt="Zoya" />
  <Person src="/people/Benjamin.webp" name="Ben" alt="Ben"/> 
  <Person src="/people/EzraS.webp" name="Ezra" alt="Ezra"/> 
  <Person src="/people/KyleA.jpg" name="Kyle" alt="Kyle"/> 

  <Person src="/people/OzzyL.webp" name="Ozzy" alt="Ozzy"/>

</div>

<h1>Field</h1>
<div class="team-grid">
  <Person src="/people/ClementineL.webp" name="Clementine" alt="Clementine"/> <!--add-->
  <Person src="/people/MilesM.webp" name="Miles" alt="Miles"/> <!--add-->
  <Person src="/people/FelixL.webp" name="Felix" alt="Felix" /> <!--add-->
  <Person src="/people/RyanW.webp" name="Ryan" alt="Ryan"/> 
</div>


<h1>Drive Team</h1>
<div class="team-grid">
  <Person src="/people/LunaS.webp" name="Luna" alt="Luna"/>
  <Person src="/people/VioletK.webp" name="Violet" alt="Violet"/>
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
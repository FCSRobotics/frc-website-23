<script>
  import Person from "$lib/Person.svelte";
  import Spacer from "$lib/Spacer.svelte";
</script>

<h1>Mentors</h1>
<div class="team-grid">
  <Person src="/people/mscho.jpg" name="Matt Schoifet" alt="Mr Schoifet" />
  <Person src="/people/akash.jpeg" name="Akash" alt="Akash" />
  <Person src="/people/ben.jpeg" name="Ben" alt="Ben" />
  <Person src="/people/mike.webp" name="Mike Dillon" alt="Mike Dillon" /> <!--add-->
</div>
<h1>Students</h1>
<div class="team-grid">
  <Person src="/people/ian.jpg" alt="Ian" name="Ian" /> <!--add-->
  <Person src="/people/jackw.jpg" name="Jack" alt="Jack" /> <!--add-->
  <Person src="/people/rishi.jpg" name="Ryan" alt="Ryan" /> <!--add-->

  <Person src="/people/charlie.jpg" name="Charlie" alt="Charlie" /> <!--add-->
  <Person src="/people/oliver.jpg" name="Oliver" alt="Oliver" /> <!--add-->
  <Person src="/people/julia.jpg" name="Julia" alt="Julia"/> <!--add-->
  <Person src="/people/maxam.png" name="Maxam" alt="Maxam" /> 

  <Person src="/people/arda.jpg" name="Arda" alt="Arda" /> <!--add-->
  <Person src="/people/clem.png" name="Clementine" alt="Clementine"/> <!--add-->
  <Person src="/people/oona.jpg" name="Oona" alt="Oona" /> <!--add-->
  <Person src="/people/elliot.jpg" name="Elliot" alt="Elliot"/> <!--add-->

  <Person src="/people/felix.jpg" name="Felix" alt="Felix" /> <!--add-->
  <Person src="/people/zoya.jpg" name="Zoya" alt="Zoya" /> <!--add-->
  <Person src="/people/sophie.jpg" name="Sophie" alt="Sophie" /> <!--add-->
  <Person src="/people/asa.jpg" name="Asa" alt="ASa" /> <!--add-->

  <Person src="/people/landon.jpg" name="Landon" alt="Landon" /> <!--add-->

  <Person src="/people/lucy.jpg" name="Lucy" alt="Lucy" /> <!--add-->
  <Person src="/people/peter.jpg" name="Peter" alt="Peter"/> <!--add-->
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

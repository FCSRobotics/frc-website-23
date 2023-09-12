<svelte:head>
  <title>Earthquakers 9094</title>
</svelte:head>

<header>
  <div id="blur">
    <img src="/logo.png" alt="Earthquakers 9094" />
    <!-- <h1>Earthquakers 9094</h1> -->
    <div role="doc-subtitle">Robotics team of Friend Central School</div>
  </div>
</header>
<p>
  The Earthquakers, established in the fall of 2022, are the robotics team
  representing Friends' Central School. Friends' Central School is a Quaker,
  community-based school. The Quaker values of simplicity, peace, equality, and
  integrity guide our interactions with ourselves and our community. In founding
  a FIRST Robotics team, we incorporate these ideas into FIRST’s mission of
  inspiring students to pursue careers in science and technology. We hope that
  by creating an accessible, collaborative robotics program, we can develop
  students with the skill sets to affect change in the world around them.
</p>

<style>
  h1 {
    margin: 0px;
  }
  [role="doc-subtitle"] {
    /* color: #c2c2c2; */
    font-size: 2rem;
  }

  p {
    font-size: 1.2em;
  }

  header {
    color: white;
    width: 100%;

    text-align: center;
    padding-top: 10rem;
    padding-bottom: 10rem;
    background: url("/hero.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    /* filter: blur(8px);
    -webkit-filter: blur(8px); */
  }

  #blur {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;

    backdrop-filter: blur(8px) brightness(60%);
    -webkit-backdrop-filter: blur(8px) brightness(60%);

    padding-top: 5rem;
    padding-bottom: 5rem;
  }
</style>

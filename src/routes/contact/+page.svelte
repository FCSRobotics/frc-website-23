<script>
  import Spacer from "$lib/Spacer.svelte";
</script>

<div id="content">
  <a id="mscho" href="mailto: mschoifet@friendscentral.org">
    <img src="/logo-vertical.png" alt="Earthquakers" />
    <div id="text">
      <h3>Matty "Robot-sized" Schoifet</h3>
      <p>Head mentor</p>
      <p>mschoifet@friendscentral.org</p>
    </div>
  </a>
</div>
<Spacer />

<style>
  #content {
    margin-top: 5vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  #mscho {
    width: max-content;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 5vw;
    flex-direction: row;
    color: white;
    background-color: var(--primary);
    padding: 2vw;
    padding-bottom: 8vh;
    padding-top: 8vh;
    border-radius: 1vw;
    height: max-content;
    text-decoration: none;
    transition: scale 500ms;
  }
  #mscho > img {
    border-radius: 1vw;
    width: 20vw;
  }
  #mscho:hover {
    scale: 1.1;
  }

  @media (max-width: 1000px) {
    #mscho {
      flex-direction: column;
    }
    #mscho > img {
      border-radius: 1vw;
      width: 50vw;
    }
  }
</style>

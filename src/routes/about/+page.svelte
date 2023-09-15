<h1>Meet the team!</h1>
<div class="team-grid">
  <img src="/people/mscho.jpg" alt="Mr Schoifet" />
  <img src="/people/jack.png" alt="Jack" />
  <img src="/people/zubin.jpg" alt="Zubin" />
  <img src="/people/alex.jpg" alt="Alex" />
  <img src="/people/landon.jpg" alt="Landon" />
</div>

<style>
  .team-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    width: 80%;
    margin: auto;
    gap: 4vw;
    place-items: center;
  }

  .team-grid > img:nth-child(1) {
    filter: saturate(0%) blur(1px);
  }

  img {
    width: 100%;
    border-radius: 30px;
  }
</style>

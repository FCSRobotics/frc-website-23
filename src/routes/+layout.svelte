<link rel="stylesheet" href="/global.css" />

<div id="container">
  <nav>
    <a href="/"><img id="logo" src="/logo.png" alt="Earthquakers 9094" /></a><a
      href="/first">What is FIRST?</a
    ><a href="/about">About our team</a><a href="/seasons">Past seasons</a><a
      href="/sponsors">Sponsors</a
    ><a href="/contact">Contact us</a>
  </nav>

  <main>
    <slot />
  </main>
</div>

<style>
  nav {
    background-color: var(--primary);
    height: 15vh;
    position: sticky;
    top: 0px;
    left: 0px;
    right: 0px;
    z-index: 999;
    color: white;
    text-decoration: none;
    display: grid;
    place-items: center;
    grid-template-columns: 1fr repeat(5, 1fr);
  }

  #container {
    height: 100%;
    display: flex;
    flex-direction: column;
  }
  main {
    height: 100%;
  }
  #logo {
    width: 100%;
  }
  a {
    color: white;
    font-size: 1.5rem;
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
</style>

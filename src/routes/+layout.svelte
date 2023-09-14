<link rel="stylesheet" href="/global.css" />
<link
  rel="stylesheet"
  href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0"
/>

<div id="container">
  <nav>
    <a id="with-logo" href="/"
      ><img id="logo" src="/logo.png" alt="Earthquakers 9094" /></a
    ><a href="/first">What is FIRST?</a><a href="/about">About our team</a><a
      href="/seasons">Past seasons</a
    ><a href="/sponsors">Sponsors</a><a href="/contact">Contact us</a>
    <span id="spacer" />
    <div id="dropdown">
      <button id="mobile-dropdown"
        ><span class="material-symbols-outlined"> menu </span></button
      >
      <div id="dropdown-content">
        <a href="/first">What is FIRST?</a><a href="/about">About our team</a><a
          href="/seasons">Past seasons</a
        ><a href="/sponsors">Sponsors</a><a href="/contact">Contact us</a>
      </div>
    </div>
  </nav>

  <main>
    <slot />
  </main>
</div>

<style>
  nav {
    background: linear-gradient(0.25turn, var(--primary), var(--accent));
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
  nav > a {
    color: white;
    font-size: 1.3vw;
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    scale: 1;
    transition: scale 0.5s;
  }

  nav > a:hover:not(:nth-child(1)) {
    /* font-size: 2rem; */
    scale: 1.5;
  }

  #dropdown {
    display: none;
  }

  #spacer {
    display: none;
  }

  #dropdown-content {
    display: none;
    position: absolute;
    right: 0px;
    padding: 2vw;
    background-color: var(--primary);
    z-index: 9999;
    border-radius: 15px;
  }

  #dropdown-content > a {
    color: white;
  }

  @media (max-width: 1000px) {
    nav > a {
      display: none;
    }
    nav > a#with-logo {
      display: flex;
    }

    #spacer {
      display: block;
    }

    nav {
      grid-template-columns: 2fr 5fr 1fr;
    }

    #dropdown {
      display: block;
    }

    #mobile-dropdown {
      color: white;
      background: none;
      border: none;
    }

    #dropdown:hover > #dropdown-content {
      display: flex;
      flex-direction: column;
      gap: 2vw;
    }
  }
</style>

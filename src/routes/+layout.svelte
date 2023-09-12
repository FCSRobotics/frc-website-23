<nav>
  <a href="/">Home</a><a href="/past-robots">Past robots</a>
  <a href="/contact">Follow us</a>
  <a href="/our-community">Our Community</a>
  <a href="/what-is-first">What is FIRST?</a>
</nav>

<main>
  <slot />
</main>

<link rel="stylesheet" href="/global.css" />

<style>
  nav {
    background-color: var(--primary);
    width: 100%;
    height: 5%;
    font-size: 1.5rem;
    /* display: flex;
		justify-content: center;
		align-items: center; */
    display: grid;
    place-items: center;
    grid-template-rows: 1fr;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
    position: fixed;
    top: 0px;
    left: 0px;
  }
  main {
    margin: 0px;
    margin-top: 2%;
    margin-bottom: 10rem;
    text-align: center;
  }
  html {
    background-color: var(--background);
  }

  nav > a {
    color: white;
    background-color: var(--primary);
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    transition: background-color 0.25s;
    text-decoration: none;
  }
  nav > a:hover,
  nav > a#selected {
    background-color: var(--accent);
  }
</style>

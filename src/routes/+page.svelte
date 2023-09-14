<header>
  <div id="headings">
    <img id="logo" src="/logo-high.png" alt="Earthquakers 9094" />
    <h2>Friends' Central School Robotics</h2>
  </div>
  <img src="" alt="" />
</header>

<style>
  #logo {
    width: max(60vw, 80%);
    height: auto;
  }

  header {
    background-image: url("/team.jpeg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center 70%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
  }

  h2 {
    font-size: max(2vw, 1rem);
  }

  #headings {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    width: 60%;
    padding: 50px;
    border-radius: 50px;
    backdrop-filter: blur(8px) brightness(50%);
  }

  @media (max-width: 600px) {
    #logo {
      content: url("/logo-vertical.png");
      height: 50vh;
      width: auto;
    }
  }
</style>

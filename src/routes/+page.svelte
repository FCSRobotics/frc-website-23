<header>
  <div id="headings">
    <img id="logo" src="/logo-high.png" alt="Earthquakers 9094" />
  </div>
</header>
<div id="matts-white-box">
  <p>
    Welcome to the homepage of The Earthquakers #9094 FIRST® Robotics
    Competition Team. We are based out of Friends’ Central School’s Center for
    Innovation and Design makerspace in Wynnewood, Pennsylvania.
  </p>
  <div id="logos">
    <a target="_blank" href="https://www.friendscentral.org/"
      ><img src="/fcs.png" alt="FCS" /></a
    ><a target="_blank" href="https://www.firstinspires.org/"
      ><img src="/FIRST.png" alt="FIRST" /></a
    ><a target="_blank" href="https://corporate.comcast.com/"
      ><img src="/comcast.png" alt="comcast" /></a
    >
  </div>
</div>

<style>
  #matts-white-box {
    background-color: white;
    padding: 5vw;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  #logos {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: row;
    width: 60%;
    gap: 5vw;
  }
  #logos > a {
    width: 50%;
  }

  #logos > a:nth-child(1) {
    filter: invert(180);
  }
  a > img {
    width: 100%;
  }

  p {
    width: 70%;
    font-size: 1.75vw;
  }
  #logo {
    width: max(60vw, 80%);
    height: auto;
  }

  header {
    background-image: url("/first.webp");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center 70%;
    padding-top: 20px;
    padding-bottom: 20px;
    height: 100vh;
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
    height: min-content;
    padding-top: 50px;
    padding-bottom: 20px;
    border-radius: 20px;
    backdrop-filter: blur(0px) brightness(50%);
  }

  @media (max-width: 900px) {
    #fcs-link {
      width: 10vw;
    }
  }

  @media (max-width: 600px) {
    #logo {
      content: url("/logo-vertical.png");
      height: 50vh;
      width: auto;
    }

    #fcs-link {
      display: none;
    }
  }
</style>

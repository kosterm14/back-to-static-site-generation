<script>
</script>

<section>
  <body>
    <!-- <label> -->
      <!-- <input type="checkbox" />
      <span class="menu"> <span class="hamburger" /> </span> -->

      <nav>
        <ul>
          <a href="/tekenmethodes"><li>Tekenmethodes</li></a>
          <a href="/kennisclips"><li>Kennisclips</li></a>
          <a href="/"><li><img src="assets\vtHBO-v1.0-Logo_1.svg" class="visual-thinking-logo"
            alt="visual-thinking-logo"></li></a>
          <a href="/over"><li>Over</li></a>
          <a href="/artikelen"><li>Artikelen</li></a>
          </ul>
        
        </nav>
    <!-- </label> -->
  </body>
</section>

<style>
  body {
    margin: 0;
    padding: 0;
    box-shadow: 0px 4px 6px -2px rgba(0, 0, 0, 0.1);
    width: 100vw;
  }

  a {
    color: var(--vtDarkBlue);
    text-decoration: none;
    cursor: pointer;
  }

  a:link {
    text-decoration: none;
  }

  nav {
    padding: 2em;
    /* margin-left: -7em; */
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: rgb(255, 252, 249);  
    width: 100vw;
    box-shadow: 0px 4px 6px -2px rgba(0, 0, 0, 0.1);
  }

  img {
    margin-left: 1em;
    margin-right: 1em;
  }

  ul {
    list-style-type: none;
    display: flex;
    color: var(--vtDarkBlue);
    font-family: var(--vtPrimaryFont);
    font-weight: 700;
    padding: 0;
    margin: 0;
    align-items: center;
    justify-content: center;
    width: 100vw;
  }

  li {
    margin-left: 1em;
    margin-right: 1em;
  }

  .visual-thinking-logo {
    max-width: 100px;
    height: auto;
  }

  /* input {
      display: none;
    } */


 @media (width<880px) {
 li {
    margin-left: 0.5em;
    margin-right: 0.5em;
  }
  
  ul {
    margin-left: 3em;
    width: 100vw;
  }

  body {
    width: 100vw;
  } 

  /* input {
      display: none;
    } */

    nav {
      background-color: rgb(255, 252, 249);
      padding: 2em;
      width: 100vw;
    }
}

  @media (width<580px) {
    /* input {
      display: none;
    } */

    /* label {
            display: none;
		} */

    a:link {
      text-decoration: none;
      font-family: var(--vtPrimaryFont), sans-serif; 
      font-weight: 700;
    }

    nav {
      background-color: rgb(255, 252, 249);
      padding: 2em;
      /* width: 100vh; */
    }

    body {
    width: 100vh;
    }

    ul {
      margin-left: 6em;
      width: 100vw;
    }
  }


  @media (width<580px) {

    *,
    *:before,
    *:after {
      box-sizing: border-box;
    }

    body {
      font-size: 1.2em;
      line-height: 1.6;
      overflow-x: hidden;
      background-color: rgb(255, 255, 255);
      width: 100vh;
    }

    nav {
      background-color: rgb(255, 252, 249);
      padding: 2em;
      /* width: 100vw; */
    }

    /* .yellowIcons {
     display: none;
    } */
/* 
    label .menu {
      position: fixed;
      right: -100px;
      top: -120px;
      z-index: 100;
      width: 200px;
      height: 200px;
      background: #ffffff;
      border-radius: 50% 50% 50% 50%;
      -webkit-transition: 0.5s ease-in-out;
      transition: 0.5s ease-in-out;
      box-shadow:
        0 0 0 0 #fff,
        0 0 0 0 #fff;
      cursor: pointer;
    }

    label .hamburger {
      position: absolute;
      top: 150px;
      left: 50px;
      width: 30px;
      height: 2px;
      background: #000000;
      display: block;
      -webkit-transform-origin: center;
      transform-origin: center;
      -webkit-transition: 0.5s ease-in-out;
      transition: 0.5s ease-in-out;
    }

    label .hamburger:after,
    label .hamburger:before {
      -webkit-transition: 0.5s ease-in-out;
      transition: 0.5s ease-in-out;
      content: "";
      position: absolute;
      display: block;
      width: 100%;
      height: 100%;
      background: #000000;
    }

    label .hamburger:before {
      top: -10px;
    }

    label .hamburger:after {
      bottom: -10px;
    }

    label input {
      display: none;
    }

    label input:checked + .menu {
      box-shadow:
        0 0 0 100vw #fff,
        0 0 0 100vh #fff;
      border-radius: 0;
    }

    label input:checked + .menu .hamburger {
      -webkit-transform: rotate(45deg);
      transform: rotate(45deg);
    }

    label input:checked + .menu .hamburger:after {
      -webkit-transform: rotate(90deg);
      transform: rotate(90deg);
      bottom: 0;
    }

    label input:checked + .menu .hamburger:before {
      -webkit-transform: rotate(90deg);
      transform: rotate(90deg);
      top: 0;
    }

    label input:checked + .menu + ul {
      opacity: 1;
    }

    label ul {
      z-index: 200;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      opacity: 0;
      transition: 0.25s 0.05s ease-in-out;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }

    li {
      margin-bottom: 1em;
      display: block;
      color: #000000;
      text-decoration: none;
    } */
  }
</style>

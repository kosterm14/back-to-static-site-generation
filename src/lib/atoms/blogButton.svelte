<section>
  <button><a href="/#">Lees meer</a></button>
</section>

<style>
  button {
    background-color: var(--vtDarkBlue);
    border-radius: 0.5em;
    list-style: none;
    border: none;
    margin: 1em;
    padding: 0.6em;
    margin-top: 29em;
  }

  button:hover {
    background-color: var(--vtRed);
  }

  a {
    font-family: var(--vtPrimaryFont);
    color: var(--vtWhite);
    text-decoration: none;
    font-weight: bold;
    font-size: 16px;
  }

  /* tablet */
  @media (max-width: 55em) {
    button {
      margin-top: 22em;
    }
  }

  /* Mobile */
  @media (max-width: 40em) {
    button {
      margin-top: 27em;
    }
  }
</style>

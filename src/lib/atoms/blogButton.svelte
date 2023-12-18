<section>
  <ul>
    <li><a href="/#">Lees meer</a></li>
  </ul>
</section>

<style>
  ul {
    display: flex;
    align-items: center;
    flex-direction: row;
  }

  li {
    background-color: var(--vtYellow);
    border-radius: 0.5em;
    list-style: none;
    margin: 1em;
    padding: 0.6em;
  }

  li:hover {
    background-color: var(--vtRed);
  }

  a {
    font-family: var(--vtPrimaryFont);
    color: var(--vtDarkBlue);
    text-decoration: none;
    font-weight: bold;
    font-size: 16px;
  }

  /* tablet */
  @media (min-width: 31em) and (max-width: 55em) {
  }

  /* mobile */
  @media (max-width: 31em) {
  }
</style>

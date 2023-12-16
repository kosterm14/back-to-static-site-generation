<section>
  <!-- CARDS - BORDER -->
  <article></article>
  <article></article>
  <article></article>
  <!-- CARDS - BORDER -->
  <article></article>
  <article></article>
  <article></article>
</section>

<style>
  section {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    flex-wrap: wrap;
    gap: 2em;
    padding: 3em;
    margin: 3em;
  }

  article {
    height: 60vh;
    width: 23vw;
    border: 4px solid var(--vtDarkBlue);
    border-radius: 0.5em;
  }

  /* tablet */
  @media (min-width: 31em) and (max-width: 55em) {
    section {
      flex-direction: row;
      justify-content: space-evenly;
      align-items: center;
      margin: -1em;
    }

    article {
      width: 39vw;
      height: 65vh;
    }
  }

  /* mobile */
  @media (max-width: 31em) {
    section {
      flex-direction: column;
      justify-content: space-evenly;
      align-items: center;
      margin: -1em;
    }

    article {
      height: 60vh;
      width: 50vw;
    }
  }
</style>

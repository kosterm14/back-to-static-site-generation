<script>
  import BlogButton from "./blogButton.svelte";
</script>

<section>
  <!-- CARDS - BORDER -->
  <article>
    <BlogButton />
  </article>
  <article>
    <BlogButton />
  </article>
  <article>
    <BlogButton />
  </article>

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
    width: 21vw;
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
      width: 11em;
      height: 17em;
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

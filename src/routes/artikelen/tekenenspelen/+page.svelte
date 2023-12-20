<script>
  import Header from "$lib/molecules/header.svelte";
  import Footer from "$lib/molecules/footer.svelte";
</script>

<header>
  <Header/>
  <section>
    <h4 class="line">Case</h4>
  </section>
</header>

<section class="backgroundcolortitle">

<h1>Tekenen en spelen met kinderen (en hun ouders)</h1>

</section>

<section>

  
</section>
<Footer/>

<style>
  .line {
    text-transform: uppercase;
    background-color: var(--vtDarkBlue);
    color: var(--vtWhite);
    font-family: var(--vtPrimaryFont);
    font-size: 0.9rem;
    padding-left: 7rem;
    padding-top: 0.2rem;
    padding-bottom: 0.2rem;
    margin-top: 0%;
    display: flex;
    align-items: center;
  }

  .backgroundcolortitle{
    background-color: rgb(240, 240, 240);
    padding: 1em;
    margin-top: -1.2em;
  }

  h1{
    font-family: var(--vtPrimaryFont);
    color: var(--vtDarkBlue);
    font-size: xxx-large;
    margin-left: 12em;
  }
</style>

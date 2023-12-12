<script>


</script>

<section>

  <nav class="footer">

  <a href="/"><img src="assets\visual-thinking-logo-footer.svg" class="logo-footer" alt="footer-logo"></a>

  <ul class="footer-menu">
    <h4>
    <a href="/over" ><li>Over</li></a>
    <a href="/artikelen" ><li>Artikelen</li></a>
    <a href="/tekenmethodes" ><li>Tekenmethodes</li></a>
    <a href="/kennisclips" ><li>Kennisclips</li></a>
    </h4>
  </ul>

  <ul class="social-media">
  <h4>Contact</h4>
  <img src="assets\social-media-icons\instagram.svg" alt="instagram">
  <a href="https://www.youtube.com/playlist?list=PLjrep0WCM97y9fznRYBVVKyDkzlT9fWEa"><img src="assets\social-media-icons\youtube.svg" alt="youtube"></a> 
  <a href="https://www.linkedin.com/in/charleymuhren/"><img src="assets\iconmonstr-linkedin-3.svg" alt="linkedIn"></a>
  <h5>© Charley Muhren, 2022</h5>
  </ul>

  </nav>
  
</section>

<style>

:root {
    --vtPrimaryFont: "rigid-square", sans-serif;
    --vtSecondaryFont: "yrsa", serif;
    --vtDarkBlue: #090940;
}

section {
    margin: 0;
    padding: 0;
    
}

.footer {
    padding-top: 3em;
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    align-items: center;
    gap: 10px; 
    background-color: rgb(240, 240, 240);
    font-family: var(--vtPrimaryFont);
}

a {
    text-decoration: none;
    color: var(--vtDarkBlue);
}

li {
    list-style-type: none;
    margin-bottom: 0.5em;
}

img {
    grid-column: 1;
    margin-right: 1em;
}

.logo-footer {
    width: 16em;
    margin-left: 6em;
}

.footer-menu {
    grid-column: 2;
    /* margin-left: 5em; */
}

.social-media {
    grid-column: 3;
    
}

@media (max-width: 500px) { 
.footer {
 display: flex;
}
}

@media (max-width: 880px) { 
.footer {
    padding-top: 3em;
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    align-items: center;
    gap: 10px; 
    max-width: 80em;
    background-color: rgb(240, 240, 240);
    font-family: var(--vtPrimaryFont);
    margin-left: 0em;
}
}

@media (max-width: 1000px) { 
.footer {
    padding-top: 3em;
    align-items: center;
    justify-content: center;
    gap: 10px;
    display: flex;
    flex-wrap: wrap;
}
}

</style>
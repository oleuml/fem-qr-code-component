<script>
</script>

<main class="grid">
  <div class="box">
    <img src="image-qr-code.png" />
    <article>
      <h2 class="bold">Improve your front-end skills by building projects</h2>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </article>
  </div>
</main>

<style>
  .grid {
    display: grid;
    place-items: center;
    height: 100vh;
  }
  article {
    margin-block: 1rem;
    margin-inline: 1rem;
  }
  h2 {
    font-size: 20px;
    text-align: center;
    color: var(--darkblue);
    padding-bottom: 1rem;
  }
  .bold {
    font-weight: 700;
  }
  p {
    font-weight: 400;
    font-size: 15px;
    line-height: normal;

    text-align: center;
    color: var(--grayishblue);
  }
  .box {
    --margin: 1.75rem;
    padding: 1em;
    background-color: white;
    border-radius: 1em;
    margin-inline: var(--margin);
    max-width: calc(375px - 2 * var(--margin));
  }
  .box img {
    border-radius: 0.75em;
  }
</style>

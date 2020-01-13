<style type="text/scss">
  .hero {
    background-image: radial-gradient(circle at top, #272c2ed3, #0e1010da),
      url("./home_bg.jpg") !important;
    height: calc(100vh - 50px) !important;
    font-family: nunito-sans, sans-serif;
    margin-top: -50px;
  }
  .title,
  .subtitle {
    color: white;
  }
  .ni {
    background: #ff2c3c;
    border-color: #ff2c3c;
    color: white;
    font-family: nunito-sans, sans-serif;
    font-weight: bold;
  }
  .ni.outlined {
    background: transparent;
  }
</style>

<svelte:head>
  <title>Neo Interactive Games</title>
</svelte:head>

<section class="hero is-fullheight">
  <div class="hero-body has-text-centered">
    <div class="container">
      <h1 class="title is-4">WE ARE</h1>
      <img src="NeoInteractive-Horizontal.svg" width="550" alt="Logo" />
      <h2 class="subtitle">
        <em>Always Forward.</em>
      </h2>
      <br />
      <br />
      <a href="about" class="button ni">About Us</a>
      &ensp;
      <a href="games" class="button ni outlined">Our Games</a>
    </div>
  </div>
</section>

<script>
  import Hero from "../components/Hero.svelte";
</script>

<style>
  .card {
    border-radius: 10px;
  }
  .image img {
    border-top-right-radius: 10px;
    border-top-left-radius: 10px;
  }
</style>

<svelte:head>
  <title>Neo Interactive Games</title>
</svelte:head>
<Hero title={'Games'} />

<br />
<section class="container">
  <div class="column is-6">
    <div class="card">
      <div class="card-image">
        <figure class="image is-16by9">
          <img src="sz-cover-ryder-169.jpg" alt="Placeholder image" />
        </figure>
      </div>
      <div class="card-content">
        <p class="title is-4">Samurai Zero</p>
        <p class="subtitle is-6">
          <strong>Release Date:</strong>
          TBD
        </p>
        <p class="subtitle is-6">
          <strong>Website</strong>
          <a href="https://samuraizero.com/">samuraizero.com</a>
        </p>
        <div class="content">
          Samurai Zero is a multiplayer action RPG set in the science fantasy
          world of Edo. Every conflict is an intense champloo of the power of
          the unknown, fusing samurai power fantasies and over-the-top action.
          In Samurai Zero, a host of characters with their own special abilities
          and personalities fight across an ever-changing fantasy landscape
          inspired by the Japanese Age of the Samurai.
        </div>
      </div>
    </div>
  </div>
</section>

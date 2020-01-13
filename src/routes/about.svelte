<script>
  import Hero from "../components/Hero.svelte";
</script>

<style>
  .container {
    margin-top: 3rem;
    font-family: nunito-sans, sans-serif;
  }
  .title {
    color: white;
    font-size: 2rem;
  }
  .body {
    color: white;
    font-size: 1.5rem;
  }
</style>

<svelte:head>
  <title>About</title>
</svelte:head>

<Hero title={'About Neo Interactive'} />

<div class="container">
  <div class="columns">
    <div class="column is-8 is-offset-2">

      <h1 class="title">Our Story</h1>
      <p class="body">
        Neo Interactive was started by four friends in 2016, under the original
        name of ICS Studios.
        <br />
        <br />
        Since our creative journey began back in 2016, Always Forward has been
        our singular mantra. From the early prototypes to more recent late night
        development sessions - Always Forward - and always with our fans in
        mind. Whether it was small steps or great leaps forward - our dedication
        was to create games fitting the vision we honed and the inspired
        experience we knew our fans would love.
      </p>
    </div>
  </div>
</div>

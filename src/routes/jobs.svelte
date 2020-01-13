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
  }
</style>

<svelte:head>
  <title>About</title>
</svelte:head>

<Hero title={'Job Openings'} />

<div class="container">
  <div class="columns">
    <div class="column has-text-centered is-8 is-offset-2">
      <br />
      <br />
      <h1 class="title is-5">
        <em>We currently have no open positions.</em>
      </h1>
    </div>
  </div>
</div>

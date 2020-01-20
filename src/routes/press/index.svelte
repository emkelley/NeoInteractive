<script>
  import Hero from "../../components/Hero.svelte";
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
  <title>Press Kits</title>
</svelte:head>

<Hero title={'Press Kits'} />

<div class="container">
  <br />
  <br />
  <br />
  <div class="columns">
    <div class="column is-8 is-offset-2 has-text-centered">
      <a
        href="press/samuraizero"
        class="title"
        style="text-decoration: underline">
        Samurai Zero
      </a>
    </div>
  </div>
</div>

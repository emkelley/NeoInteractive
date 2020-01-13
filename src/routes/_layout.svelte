<script>
  import Nav from "../components/Nav.svelte";

  export let segment;
</script>

<style>
  :global(body) {
    background-image: radial-gradient(circle at top, #272c2e, #0e1010);
    background-size: cover;
    background-repeat: no-repeat;
    min-height: 100vh;
  }
</style>

<Nav {segment} />

<main>
  <slot />
</main>

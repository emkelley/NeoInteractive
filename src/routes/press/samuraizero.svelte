<script>
  import Hero from "../../components/Hero.svelte";
</script>

<style>
  .container {
    margin-top: 3rem;
    font-family: nunito-sans, sans-serif;
  }
  .title {
    color: #ff2c3c;
  }
  p {
    color: white;
    font-size: 1.2rem;
  }
  .subtitle {
    color: white;
    font-weight: bold;
  }
  .contact {
    text-align: right;
  }
</style>

<svelte:head>
  <title>Samurai Zero Press Kit</title>
</svelte:head>

<Hero title={'Samurai Zero Press Kit'} />

<div class="container">
  <div class="columns is-multiline">
    <div class="column is-8 is-offset-2">

      <img src="sz-press-cover.jpg" alt="Samurai Zero Press Banner" />
      <br />
      <br />
      <iframe
        title="SZ Vision"
        width="100%"
        height="375"
        src="https://www.youtube-nocookie.com/embed/aTfTqCmtMJA?controls=0"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope;
        picture-in-picture"
        allowfullscreen />
      <br />
      <br />
      <br />
      <div class="columns">
        <div class="column is-6">
          <h1 class="title">Story</h1>
          <p class="body">
            Samurai Zero is a Multiplayer Action game set in the science-fantasy
            world of Edo. Every conflict is an intense champloo of the power of
            the unknown, fusing samurai power fantasies and over-the-top action.
            In Samurai Zero, a host of characters with their own special
            abilities and personalities fight across an ever-changing fantasy
            landscape inspired by the Japanese Age of the Samurai.
          </p>
        </div>
        <div class="column is-6 contact">
          <h1 class="title">Contact</h1>
          <p>
            Marlowe Crawford - Game Designer
            <br />
            marlowe@samuraizero.com
            <br />
            <br />
            Eric Kelley - Community Manager
            <br />
            eric@samuraizero.com
            <br />
            <br />
            Twitter/Facebook/Instagram
            <br />
            @PlaySamuraiZero
            <br />
            <br />
            Website
            <br />
            <a href="https://samuraizero.com">samuraizero.com</a>
          </p>

        </div>
      </div>

      <br />
      <br />
    </div>
    <div class="column is-8 is-offset-2">

      <div id="intro">
        <div class="columns is-multiline">
          <div class="column is-12 has-text-centered">
            <div class="section-title-wrapper">
              <h1 class="title section-title">Key Features</h1>
              <hr />
            </div>
          </div>
          <div class="column is-4 intro-item">
            <h1 class="title intro-item-title" style="color: white">
              Art of the Samurai
            </h1>
            <p class="intro-item-content">
              Perfect your skills in a team-focused arena fighter, mastering the
              various skills and strengths of powerful Samurai.
            </p>
          </div>
          <div class="column is-4 intro-item">
            <h1 class="title intro-item-title" style="color: white">
              Global Preacher
            </h1>
            <p class="intro-item-content">
              Discover everything the world of Edo has to offer. From ancient
              mystical ruins to technologically marvelous capitals, become
              enraptured in the vast history of conflict that has shaped the
              world.
            </p>
          </div>
          <div class="column is-4 intro-item">
            <h1 class="title intro-item-title" style="color: white">
              Looking For a Hero
            </h1>
            <p class="intro-item-content">
              More than swordsmanship and ancient powers, the Samurai have
              conflicts both deeply personal and with the state of the world.
              Become invested in an eclectic cast and bear witness to the
              journeys they take to change both themselves and the world of Edo.
            </p>
          </div>

          <div class="column is-12 has-text-centered">
            <br />
            <br />
            <br />
          </div>
          <div class="column is-12 has-text-centered">
            <div class="section-title-wrapper">
              <h1 class="title section-title">Screenshots</h1>
              <hr />
            </div>
          </div>
          <div class="column is-6 screenshot">
            <img src="ss-wraith.jpg" alt="Wraith" />
          </div>
          <div class="column is-6 screenshot">
            <img src="ss-ryder.jpg" alt="Ryder" />
          </div>
          <div class="column is-6 screenshot">
            <img src="ss-luna.jpg" alt="Luna" />
          </div>
          <div class="column is-6 screenshot">
            <img src="ss-forest.jpg" alt="Forest of Visions" />
          </div>
          <div class="column is-6 screenshot">
            <img src="ss-cave.jpg" alt="Cave of Dreams" />
          </div>
          <div class="column is-6 screenshot">
            <img src="ss-sunken.jpg" alt="Sunken Ambition" />
          </div>
        </div>
      </div>
    </div>
    <div class="column is-12 has-text-centered">
      <br />
      <br />
      <br />
    </div>
    <div class="column is-8 is-offset-2">

      <div class="columns is-multiline">
        <div class="column has-text-centered">

          <h1 class="title has-text-centered">Logos & Branding</h1>
          <hr />
          <br />
          <h2 class="subtitle">Samurai Zero Logo</h2>
          <br />
          <img
            src="sz-logo-main-large.png"
            width="500"
            alt="Samurai Zero Logo" />
          <br />
          <br />
          <br />
          <br />
          <h2 class="subtitle">Neo Interactive Logo</h2>
          <br />
          <img
            src="NeoInteractive.svg"
            width="300"
            alt="Neo Interactive Logo" />
          <br />
          <br />
          <br />
          <br />
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <br />

  </div>

</div>

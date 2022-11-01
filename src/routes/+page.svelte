<svelte:head>
  <title>JAS &#x2022; Developer</title>
</svelte:head>

<div class="wrapper">
  <section id="home" class="section">
    <h1 class="section__title">Jacob Alexander Schroeder</h1>
    <p class="section__subtitle">
      Developer&nbsp;<span class="section__subtitle--italic-bold">&amp;</span
      >&nbsp;Designer
    </p>
  </section>

  <section id="about" class="section">
    <h1 class="section__title">About</h1>
  </section>

  <section id="works" class="section">
    <h1 class="section__title">Works</h1>
  </section>

  <section id="contact" class="section">
    <h1 class="section__title">Contact</h1>
  </section>
</div>

<style lang="sass">
  .wrapper
    scroll-snap-type: y mandatory
    overflow-y: scroll
    max-height: 100vh


  .section
    height: 100vh
    scroll-snap-align: start
    position: relative

    &__title
      width: 30.0rem
      padding-top: 4.0rem
      padding-inline: 4.0rem
      font-weight: 300
      text-align: center

    &__subtitle
      width: 30.0rem
      font-size: 1.8rem
      text-align: center
      padding-inline: 4.0rem

      &--italic-bold
        font-style: italic
        font-weight: bold

    &#about
      color: $light
      background-color: $green

    &#works
      color: $dark
      background-color: $sakura

    &#contact
      color: $light
      background-color: $red
</style>

<template>
  <div>
    <div class="is-hidden-mobile">
      <section class="hero is-fullheight is-default is-centered is-link is-cover-page">
        <p class="has-text-right sticky" style="display: hidden">
          <a href="/about" class="button is-medium is-warning is-inverted">
            Learn more
          </a>
        </p>

        <div class="hero-body" />
      </section>
    </div>
    <div class="is-hidden-tablet">
      <section class="hero is-fullheight is-default is-centered is-link is-mobile-cover-page">
        <p class="has-text-right sticky" style="display: hidden">
          <a href="/about" class="button is-medium is-warning is-inverted">
            Learn more
          </a>
        </p>

        <div class="hero-body" />
      </section>
    </div>
  </div>
</template>
  
<script>
export default {
  props: {}
}
</script>

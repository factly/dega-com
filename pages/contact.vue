<template>
  <div>
    <section class="hero is-fullheight is-default is-centered is-link">
      <div class="hero-body">
        <div class="container has-text-centered">
          <contact />
        </div>
      </div>
      <div class="hero-foot">
        <div class="container">
          <p class="has-text-centered">
            <a href="#contact" class="has-text-warning">Write to us if you are interested to try Dega for your fact check initiatives.</a>
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Contact from '~/components/Contact'

export default {
  name: 'ContactUs',

  components: {
    Contact
  }
}
</script>

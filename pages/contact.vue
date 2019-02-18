<template>
  <div>
    <section class="hero is-fullheight is-default is-centered is-link">
      <div class="hero-body">
        <div class="container">
          <contact />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Contact from '~/components/Contact'

export default {
  name: 'ContactPage',

  components: {
    Contact
  }
}
</script>

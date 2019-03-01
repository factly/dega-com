<template>
  <div>
    <section class="hero is-fullheight is-default is-centered is-link">
      <div class="hero-body">
        <div class="container">
          <contactus />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Contactus from '~/components/Contactus'

export default {
  name: 'ContactUsPage',

  components: {
    Contactus
  }
}
</script>

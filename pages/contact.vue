<template>
  <div>
    <hero />
    <contact />
  </div>
</template>

<script>
import Hero from '~/components/Hero'
import Contact from '~/components/Contact'

export default {
  name: 'ContactUs',

  components: {
    Hero,
    Contact
  }
}
</script>

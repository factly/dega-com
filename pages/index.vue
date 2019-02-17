<template>
  <div>
    <hero />
    <about />
    <features />
    <contact />
  </div>
</template>

<script>
import Hero from '~/components/Hero'
import About from '~/components/About'
import Features from '~/components/Features'
import '~//node_modules/bulma-timeline/dist/css/bulma-timeline.min.css'

export default {
  name: 'HomePage',

  components: {
    Hero,
    About,
    Features
  }
}
</script>

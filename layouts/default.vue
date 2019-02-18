<template>
  <div>
    <nav id="navbar" class="navbar has-shadow is-fixed-top">
      <div class="navbar-brand">
        <a class="navbar-item" href="/">
          <img src="@/assets/images/logo.png" alt="Dega: Open source fact check publishing platform." width="112" height="28">
        </a>
        <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
          <span />
          <span />
          <span />
        </div>
      </div>

      <div class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item" href="#about">
            <span class="icon">
              <i class="fas fa-info-circle" />
            </span>
            <span>About</span>
          </a>
          <a class="navbar-item" href="/features">
            <span class="icon">
              <i class="fas fa-award" />
            </span>
            <span>Features</span>
          </a>
          <a class="navbar-item" href="/team">
            <span class="icon">
              <i class="fas fa-users" />
            </span>
            <span>Team</span>
          </a>
          <a class="navbar-item" href="/contact">
            <span class="icon">
              <i class="fas fa-envelope" />
            </span>
            <span>Contact</span>
          </a>
          <a class="navbar-item" href="#docs">
            <span class="icon">
              <i class="fas fa-book" />
            </span>
            <span>Docs</span>
          </a>
        </div>
      </div>
      <!--<div class="container" />-->
    </nav>

    <section class="main-content">
      <nuxt />
    </section>

    <!-- Footer -->
    <footer class="footer has-background-primary has-text-white" style="padding-top: 1rem; padding-bottom: 1rem">
      <div class="has-text-centered">
        <p>
          The project is funded by <strong class="has-text-warning">Google Inc.</strong> and is developed by
          <strong class="has-text-warning">Factly Media & Research.</strong>
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' }
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: { name: 'inspire' }
        }
      ]
    }
  }
}
</script>

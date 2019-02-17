<template>
  <section id="contact" class="section has-background-primary">
    <div class="container">
      <div class="section-heading is-marginless">
        <h3 class="title is-2">
          Contact
        </h3>
        <h4 class="subtitle is-5">
          We love to hear from you if you have any comments or if you want to give Dega a try for your fact-checking initiative.
        </h4>
      </div>
      <br>
    </div>
    <form name="contact" method="POST" data-netlify="true">
      <p>
        <label>Your Name: <input type="text" name="name"></label>
      </p>
      <p>
        <label>Your Email: <input type="email" name="email"></label>
      </p>
      <p>
        <label>Message: <textarea name="message" /></label>
      </p>
      <p>
        <button type="submit">
          Send
        </button>
      </p>
    </form>
  </section>
</template>

<script>
export default {
  props: {}
}
</script>

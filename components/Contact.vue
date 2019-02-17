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
      <div class="field">
        <label class="label">Name</label>
        <div class="control">
          <input class="input" type="text" placeholder="full name" name="fullName">
        </div>
      </div>
      <div class="field">
        <label class="label">Organisation</label>
        <div class="control">
          <input class="input" type="text" placeholder="organisation name" name="organisation">
        </div>
      </div>
      <div class="field">
        <label class="label">Email</label>
        <div class="control has-icons-left">
          <input class="input" type="email" placeholder="valid email address" name="email">
          <span class="icon is-small is-left">
            <i class="fas fa-envelope" />
          </span>
        </div>
      </div>

      <div class="field">
        <label class="label">Phone</label>
        <div class="control has-icons-left">
          <input class="input" type="text" placeholder="include the country code" name="phone">
          <span class="icon is-small is-left">
            <i class="fas fa-phone" />
          </span>
        </div>
      </div>
      <div class="field">
        <label class="label">Message</label>
        <div class="control">
          <textarea class="textarea" placeholder="please be as descriptive as possible" name="message" />
        </div>
      </div>
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

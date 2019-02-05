<template>
  <section class="container">
    <div class="columns">
      <div class="column is-half level">
        <div class="level-left">
          <img src="~assets/images/contact_us.svg" alt>
        </div>
      </div>
      <div class="column is-half level-right">
        <p class="title">We always love to hear from you!</p>
        <p
          class="subtitle is-size-4"
        >Contact us through the form below if you have any query or want to work together;</p>
        <br>
        <br>
        <form action="https://formspree.io/boadziedaniel43@gmail.com" method="POST">
          <div class="field">
            <p class="control has-icons-left">
              <input class="input is-medium" type="text" placeholder="name" name="name">
              <span class="icon is-small is-left">
                <i class="fas fa-user"></i>
              </span>
            </p>
          </div>
          <div class="field">
            <p class="control has-icons-left has-icons-right">
              <input class="input is-medium" type="email" placeholder="Email" name="_replyto">
              <span class="icon is-small is-left">
                <i class="fas fa-envelope"></i>
              </span>
              <span class="icon is-small is-right">
                <i class="fas fa-check"></i>
              </span>
            </p>
          </div>
          <div class="field">
            <div class="control">
              <textarea class="textarea is-medium" placeholder="message" name="message"></textarea>
            </div>
          </div>
          <div class="field">
            <p class="control">
              <button class="button is-info is-rounded is-large">Send</button>
            </p>
          </div>
        </form>
      </div>
    </div>
  </section>
</template>

<style scoped>
.columns {
  margin-top: 3rem;
  margin-bottom: 4rem;
}

.container {
  margin-bottom: -20px;
}

img {
  width: 500px;
  height: 44rem;
}
</style>

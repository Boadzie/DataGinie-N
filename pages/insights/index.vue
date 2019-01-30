<template>
  <section class="container">
    <div class="columns has-text-centered">
      <div class="column is-12">
        <h1 class="title">Get insight in the Categories below</h1>
      </div>
    </div>
    <div class="columns">
      <div class="column is-3">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~/assets/images/energy.svg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media-content has-text-centered">
              <nuxt-link class="title" to="/insights/energy">Energy</nuxt-link>
            </div>
          </div>
        </div>
      </div>
      <div class="column is-3">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~/assets/images/transport.svg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media-content has-text-centered">
              <nuxt-link class="title" to="/insights/transport">Transport</nuxt-link>
            </div>
          </div>
        </div>
      </div>
      <div class="column is-3">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~/assets/images/agric.svg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media-content has-text-centered">
              <nuxt-link class="title" to="/insights/agriculture">Agriculture</nuxt-link>
            </div>
          </div>
        </div>
      </div>
      <div class="column is-3">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~/assets/images/finance.svg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media-content has-text-centered">
              <nuxt-link class="title" to="/insights/finance">Finance</nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="columns">
      <div class="column is-3">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~/assets/images/education.svg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media-content has-text-centered">
              <nuxt-link class="title" to="/insights/education">Education</nuxt-link>
            </div>
          </div>
        </div>
      </div>
      <div class="column is-3">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~/assets/images/health.svg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media-content has-text-centered">
              <nuxt-link class="title" to="/insights/health">Health</nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
h1 {
  margin-top: 2rem;
  margin-bottom: 2rem;
}

section {
  margin-bottom: 3rem;
  margin: 40px;
}
</style>

<template>
  <section class="container">
    <div class="columns has-text-centered">
      <div class="column is-12">
        <h1 class="title">Intituitive Visualizations on Energy</h1>
      </div>
    </div>
    <div class="columns">
      <div class="column level is-3">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~/assets/images/energy.svg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media-content has-text-centered">
              <nuxt-link
                class="subtitle"
                to="/insights/energy/southern_ghana_energy"
              >Electricity Customers in Southern Ghana - 2014</nuxt-link>
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


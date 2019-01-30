<template>
  <span>
    <section class="hero is-info is-small header-image">
      <!-- Hero head: will stick at the top -->
      <div class="hero-head"></div>

      <!-- Hero content: will be in the middle -->
      <div class="hero-body">
        <div class="container columns level">
          <div class="column has-text-centered is-half level-left">
            <h1 class="title is-2">Informed Decisions produce wins;</h1>
            <h3 class="is-size-4">intuitive visualization uncover insight that inform decisions.</h3>
            <br>
            <div class="space">
              <nuxt-link class="button is-success is-rounded is-large" to="insights">Learn more</nuxt-link>
            </div>
          </div>
          <div class="column is-half level-right">
            <img
              width="100%"
              height="50%"
              src="~/assets/images/data_trends.svg"
              class="step__image"
            >
          </div>
        </div>
      </div>
    </section>
    <Feature/>
  </span>
</template>

<script>
import Feature from "~/components/Feature";
export default {
  components: {
    Feature
  }
};
</script>

<style scoped>
section {
}
</style>

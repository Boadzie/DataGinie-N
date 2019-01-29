<template>
  <span>
    <section class="hero is-info is-small header-image">
      <!-- Hero head: will stick at the top -->
      <div class="hero-head"></div>

      <!-- Hero content: will be in the middle -->
      <div class="hero-body">
        <div class="container columns level">
          <div class="column is-half has-text-centered level-left">
            <em class="title">Informed Decisions produce wins;</em>
            <br>
            <i class="subtitle">intuitive visualization uncover insight that inform decisions.</i>
            <br>
            <br>
            <div class="space">
              <nuxt-link class="button is-success is-rounded is-large" to="insights">Learn more</nuxt-link>
            </div>
          </div>
          <div class="column is-half level-right">
            <img
              width="100%"
              height="30rem"
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
</style>

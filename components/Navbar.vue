<template>
  <nav class="navbar is-info">
    <div class="container">
      <div class="navbar-brand">
        <nuxt-link
          class="navbar-item"
          to="/"
          style="font-weight:bolder; text-transform:uppercase;letter-spacing:5px;"
        >DataGinie</nuxt-link>
        <span class="navbar-burger burger" data-target="navMenu">
          <span></span>
          <span></span>
          <span></span>
        </span>
      </div>
      <div id="navMenu" class="navbar-menu">
        <div class="navbar-end">
          <nuxt-link to="/" class="navbar-item">Home</nuxt-link>
          <div class="navbar-item has-dropdown is-hoverable">
            <nuxt-link class="navbar-link" to="/insights">Insights</nuxt-link>
            <div class="navbar-dropdown is-boxed">
              <nuxt-link class="navbar-item" to="/insights/energy">Energy</nuxt-link>
              <nuxt-link class="navbar-item" to="/insights/education">Education</nuxt-link>
              <nuxt-link class="navbar-item" to="/insights/finance">Finance</nuxt-link>
              <nuxt-link class="navbar-item" to="/insights/health">Health</nuxt-link>
              <nuxt-link class="navbar-item" to="/insights/transport">Transport</nuxt-link>
              <nuxt-link class="navbar-item" to="/insights/agriculture">Agriculture</nuxt-link>
            </div>
          </div>

          <nuxt-link to="/about" class="navbar-item">About</nuxt-link>
          <nuxt-link to="/contact" class="navbar-item">Contact</nuxt-link>
        </div>
      </div>
    </div>
  </nav>
</template>

<script >
export default {};
</script>

<style scoped>
</style>

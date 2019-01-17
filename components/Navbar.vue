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
            <a class="navbar-link" href>Insights</a>
            <div class="navbar-dropdown is-boxed">
              <a class="navbar-item" href>Energy</a>
              <a class="navbar-item" href>Transport</a>
              <a class="navbar-item" href>Agriculture</a>
              <a class="navbar-item" href>Finance</a>
              <hr class="navbar-divider">
              <a class="navbar-item" href>Education</a>
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
data: {
}
methods: {
}
</script>

<style scoped>
</style>

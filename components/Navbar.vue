<template>
  <nav class="navbar is-info">
    <div class="container">
      <div class="navbar-brand">
        <a
          class="navbar-item"
          href="#"
          style="font-weight:bolder; text-transform:uppercase;letter-spacing:5px;"
        >DataGinie</a>
        <span class="navbar-burger burger" data-target="navMenu">
          <span></span>
          <span></span>
          <span></span>
        </span>
      </div>
      <div id="navMenu" class="navbar-menu">
        <div class="navbar-end">
          <a href="#" class="navbar-item is-active">Home</a>
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

          <a href="#" class="navbar-item">About</a>
          <a href="#" class="navbar-item">Team</a>
          <a href="#" class="navbar-item">Contact</a>
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

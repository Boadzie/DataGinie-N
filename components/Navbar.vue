<template>
  <div>
    <no-ssr>
      <nav class="navbar is-info" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <nuxt-link
            class="navbar-item"
            to="/"
            style="font-weight:bolder; text-transform:uppercase;letter-spacing:5px;"
          >DataGinie</nuxt-link>
          <a
            role="button"
            class="navbar-burger"
            aria-label="menu"
            aria-expanded="false"
            @click="isOpen = !isOpen"
            v-bind:class="{'is-active': isOpen}"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>
        <div class="navbar-menu" v-bind:class="{'is-active': isOpen}">
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
      </nav>
      <!-- <nav class="navbar is-light" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a
            role="button"
            class="navbar-burger"
            aria-label="menu"
            aria-expanded="false"
            @click="isOpen = !isOpen"
            v-bind:class="{'is-active': isOpen}"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>
        <div class="navbar-menu" v-bind:class="{'is-active': isOpen}">
          <div class="navbar-end">
            <router-link to="/" class="navbar-item is-tab">Home</router-link>
            <router-link to="/about" class="navbar-item is-tab">About</router-link>
            <router-link to="/else" class="navbar-item is-tab">Something Else</router-link>
          </div>
        </div>
      </nav>-->
    </no-ssr>
  </div>
</template>

<script >
export default {
  data: () => {
    return {
      isOpen: false
    };
  }
};
</script>

<style scoped>
</style>

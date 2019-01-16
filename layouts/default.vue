<template>
  <div>
    <navbar/>
    <nuxt/>
    <hr style="border:1px solid #F9F5F4">
    <Footer/>
  </div>
</template>


<script>
import Navbar from "~/components/Navbar";
import Footer from "~/components/Footer";

export default {
  components: {
    Navbar,
    Footer
  }
};
</script>


<style>
html {
  font-family: "Strait", sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: beige;
}
</style>

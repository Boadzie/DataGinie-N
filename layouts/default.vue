<template>
  <div>
    <navbar/>
    <nuxt/>
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
  font-family: "Krub", sans-serif;
  font-size: 14px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: #fff;
}
</style>

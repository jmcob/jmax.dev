<template>
  <NavBar />
  <div class="about">
    <h1>Coded by Jean-Maxime Cobac,</h1>
    <h2>during spring and summer of 2022, using Vue.js 3.</h2>
    <h3>You can also visit <a href="https://www.jmxi.art">jmxi.art</a></h3>
    <br />
    <img alt="About logo" src="../assets/about.png" />
    <p>Version 3.7 error edition</p>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  name: "AboutView",
  components: {
    NavBar,
  },
  created() {
    document.title = "About - Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>

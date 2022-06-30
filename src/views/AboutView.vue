<template>
  <div class="about">
    <h1>Coded by Jean-Maxime Cobac,</h1>
    <h2>during May and June of 2022, using Vue.js 3.</h2>
    <img alt="About logo" src="../assets/about.png" />
    <p>Version 3.5.8 Sky edition</p>
  </div>
</template>

<script>
export default {
  name: "AboutView",

  created() {
    document.title = "About - Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>

<template>
  <div class="about">
    <h1>Coded by Jean-Maxime Cobac,</h1>
    <h2>during spring and summer of 2022, using Vue.js 3.</h2>
    <img alt="About logo" src="../assets/about.png" />
    <p>Version 3.7 error edition</p>
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

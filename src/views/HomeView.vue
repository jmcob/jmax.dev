<template>
  <NavBar />
  <div class="home">
    <img alt="jmax.dev logo" src="../assets/logo.png" />
    <HelloWorld msg="Bienvenue sur jmax.dev" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import NavBar from "@/components/NavBar.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    NavBar,
  },
  created() {
    document.title = "Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>

<style>
img {
  border-radius: 10px;
}
</style>

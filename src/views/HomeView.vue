<template>
  <div class="home">
    <img alt="jmax.dev logo" src="../assets/logo.png" />
    <HelloWorld msg="Bienvenue sur jmax.dev" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>

<style>
img {
  border-radius: 10px;
}
</style>

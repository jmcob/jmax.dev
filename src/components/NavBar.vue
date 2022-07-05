<template>
  <nav>
    <div class="router"><router-link to="/">jmax.dev</router-link></div>
    <div class="router"><router-link to="/cv">CV</router-link></div>
    <div class="router">
      <router-link to="/portfolio">Portfolio</router-link>
    </div>
    <div class="router"><router-link to="/contact">Contact</router-link></div>
    <div class="router"><router-link to="/about">A propos</router-link></div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
};
</script>
<style scoped>
nav {
  display: flex;
  flex-direction: row;
  justify-content: center;
  flex-wrap: wrap;
}
.router {
  margin: 12px;
}
</style>

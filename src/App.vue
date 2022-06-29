<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/cv">CV</router-link> |
    <router-link to="/portfolio">Portfolio</router-link> |
    <router-link to="/contact">Contact</router-link> |
    <router-link to="/about">A propos</router-link>
  </nav>
  <router-view />
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/cv">CV</router-link> |
    <router-link to="/portfolio">Portfolio</router-link> |
    <router-link to="/contact">Contact</router-link> |
    <router-link to="/about">A propos</router-link>
  </nav>
</template>

<script>
export default {
  name: "app",
  created() {
    document.title = "Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  font-size: x-large;
}

nav a {
  font-weight: bold;
  color: darkslategray;
}

nav a.router-link-exact-active {
  color: crimson;
}
</style>

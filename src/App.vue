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
.hello {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.cadre {
  background: rgb(10, 145, 255);
  background: linear-gradient(
    318deg,
    rgba(10, 145, 255, 1) 0%,
    rgba(90, 181, 255, 1) 3%,
    rgba(152, 209, 255, 1) 7%,
    rgba(218, 238, 255, 1) 89%,
    rgba(255, 255, 255, 1) 100%
  );
  border-radius: 5px;
  max-width: 550px;
  padding: 0 45px 15px 45px;
  box-shadow: 1px 1px midnightblue;
  margin-top: 20px;
}

.cadre img {
  position: relative;
  bottom: 35px;
}
</style>

<template>
  <router-view />
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
@import url("https://fonts.googleapis.com/css2?family=Dosis:wght@200;500;700&family=Finlandica:ital,wght@0,400;0,700;1,400&display=swap");
* {
  background-color: cornsilk;
}
#app {
  font-family: "Dosis", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  font-family: "Finlandica", sans-serif;
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
p {
  font-size: large;
}

h3 {
  margin-bottom: 0;
}
h2 {
  color: midnightblue;
}
.hello {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.cadre {
  border-radius: 15px;
  max-width: 650px;
  padding: 20px 45px 45px 45px;
  outline: 1px solid crimson;
  margin: 20px 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.img {
  padding: 0px;
  margin: 20px;
}
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: transparent;
}
.projects {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  grid-gap: 5%;
}
.card {
  width: 45%;
}
.img {
  box-sizing: border-box;
  box-shadow: 5px 5px 5px white;
  width: 81px;
  height: 81px;
}
.vue {
  color: #4caf50;
  font-weight: bold;
}
</style>

<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Bonjour, je suis développeur, pour vous servir !</h2>
    <p>
      J'ai été formé chez OpenClassrooms, en 2021/2022, en tant que développeur
      web.
    </p>

    <h3><router-link to="/cv">Voici mon CV.</router-link></h3>

    <h3><a href="https://github.com/jmcob"> Et voici ma page Github.</a></h3>

    <br />
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  color: darkblue;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: crimson;
}
</style>

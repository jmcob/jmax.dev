<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Bonjour, je suis développeur, pour vous servir !</h2>
    <p>
      J'ai été formé chez OpenClassrooms, en 2021/2022. <br />
      Je cherche un premier emploi de
      <strong>développeur web javascript</strong>, je suis spécialisé en
      <span class="vue">vue-js 3</span>.
      <br />
      <br />
      Je suis disponible, vivant, prêt pour une opportunité intéressante.
      <br />
      <br />
      Vous pouvez naviguer sur ce site afin de mieux me connaître.
      <br />
      Merci
    </p>
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
.vue {
  color: #4caf50;
  font-weight: bold;
}
</style>

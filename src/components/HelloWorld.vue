<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Bonjour, je suis développeur, pour vous servir !</h2>
    <p>
      J'ai été formé chez OpenClassrooms, en 2021/2022. <br />
      Je cherche un premier emploi de développeur web javascript, je suis
      spécialisé en vue-js 3.
      <br />
      Je suis disponible, vivant, prêt pour une opportunité intéressante.
      <br />
      Vous pouvez naviguer sur ce site afin de mieux me connaître.
    </p>

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

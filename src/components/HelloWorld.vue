<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="cadre">
      <h2>Bonjour, je suis développeur, pour vous servir !</h2>
      <p>
        J'ai été formé chez OpenClassrooms, en 2021/2022. <br />
        Je travaille actuellement chez Géosoft Aquitaine comme
        <strong>développeur web JavaScript</strong>, je suis spécialisé en
        <span class="vue">Vue.js et son environnement</span>.
        <br />
        <br />
        Je suis disponible, vivant.
        <br />
        <br />
        Vous pouvez naviguer sur ce site afin de mieux me connaître.
        <br />
        <br />
        <span class="merci"> Merci </span>
      </p>
    </div>
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

a {
  color: crimson;
}
.merci {
  transition: 200ms;
}
.merci:hover {
  font-size: xx-large;
  cursor: default;
  font-weight: bold;
  color: crimson;
}
</style>

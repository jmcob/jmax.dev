<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="cadre">
      <h2>Bonjour, je suis développeur, pour vous servir !</h2>
      <p>
        J'ai été formé chez OpenClassrooms, en 2021/2022. <br />
        Je cherche un premier emploi de
        <strong>développeur web JavaScript</strong>, je suis spécialisé en
        <span class="vue">Vue.js 3</span>.
        <br />
        <br />
        Je suis disponible, vivant, prêt pour une opportunité intéressante.
        <br />
        <br />
        Vous pouvez naviguer sur ce site afin de mieux me connaître.
        <br />
        <br />
        Merci
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
.vue {
  color: #4caf50;
  font-weight: bold;
}
</style>

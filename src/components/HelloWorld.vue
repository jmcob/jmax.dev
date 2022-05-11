<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Projets OpenClassrooms</h2>
    <p>
      J'ai été formé chez OpenClassrooms, en 2021/2022, en tant que développeur
      web.<br />
      Voici quelques-uns des projets que j'ai réalisé :
    </p>
    <h3>
      Projet 2, une maquette HTML/CSS :
      <a href="http://reservia.jmax.dev/"> Reservia</a>
    </h3>
    <h3>
      Projet 3, un MVP mobile first avec animations CSS :
      <a href="http://ohmyfood.jmax.dev/"> OhMyFood</a>
    </h3>

    <h3>
      Projet 5, un site ecommerce :
      <a href="http://kanap.jmax.dev/"> Kanap</a>
    </h3>
    <h3>
      Projet 6, le backend simple d'une appli collaborative de cuisine :
      <a href="https://www.jmax.dev/html/projets/piiquante.html">
        description de Piiquante</a
      >
    </h3>
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

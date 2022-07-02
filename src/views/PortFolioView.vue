<template>
  <NavBar />
  <div class="hello">
    <PortFolioHeader />

    <h2>
      Je vous invite à visiter
      <a href="https://github.com/jmcob"> ma page Github</a>
    </h2>
    <br />
    <br />
    <div class="cadre">
      <div class="content">
        <div class="img">
          <img alt="Port Folio premier logo" src="../assets/PF.png" />
        </div>
        <br />
        <h2>Projets OpenClassrooms</h2>
        <p>Voici quelques-uns des projets que j'ai réalisé :</p>
        <h3>
          <a href="http://reservia.jmax.dev/">Reservia</a>
        </h3>
        <p>Une maquette HTML/CSS à réaliser pour le projet 2.</p>
        <h3>
          <a href="http://ohmyfood.jmax.dev/"> OhMyFood</a>
        </h3>
        <p>Projet 3, un MVP mobile first avec animations CSS.</p>
        <h3>
          <a href="http://kanap.jmax.dev/"> Kanap</a>
        </h3>
        <p>Projet 5, un site e-commerce en JavaScript Vanilla</p>
        <h3><router-link to="/piiquante">Piiquante</router-link></h3>
        <p>
          Projet 6, le backend simple d'une appli collaborative de cuisine. En
          JavaScript node.js, express et MongoDB.
        </p>
        <h3>
          <a href="https://youtu.be/ZzJ1LImNdZc"
            >Démo de Groupomania (sur YouTube)</a
          >
        </h3>
        <p>
          Le projet 7 est un réseau social qui n'est pas en ligne. <br />
          Une courte vidéo de présentation est disponible sur Youtube.
          <br />
          Ce projet a été réalisé avec express et Vue.js 3, donc le backend et
          le frontend en JavaScript. Il utilise MySQL.
        </p>
      </div>
    </div>
    <br />
    <br />
    <br />
    <div class="cadre">
      <div class="content">
        <div class="img">
          <img alt="Port Folio premier logo" src="../assets/PF2.png" />
        </div>
        <br />
        <h2>Projets personnels</h2>
        <h3><a href="https://play.jmax.dev/">JavaScript Playground</a></h3>
        <p>
          Trois petits projets d'entrainement qui m'ont permis d'apprendre ce
          langage.
        </p>
        <h3><a href="https://todo.jmax.dev/">Task Tracker</a></h3>
        <p>Un projet Vue3 dont j'ai réalisé le back-end.</p>
        <h3><a href="https://www.jmxi.art/">jmxi.art</a></h3>
        <p>Un projet artistique religieux personnel.</p>
      </div>
    </div>
  </div>
  <br />
  <NavBar />
</template>

<script>
import PortFolioHeader from "@/components/PortFolioHeader.vue";
import NavBar from "@/components/NavBar.vue";

export default {
  name: "PortFolioView",
  components: {
    PortFolioHeader,
    NavBar,
  },
  created() {
    document.title =
      "Portfolio - Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>
<style scoped>
h2 {
  color: darkblue;
}
.img {
  /* img size is not the same (77 instead of 81) */
  width: 77px;
  height: 77px;
}
</style>

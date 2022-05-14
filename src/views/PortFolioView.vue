<template>
  <PortFolioHeader />
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
  <h3>Piiquante</h3>
  <p>
    Projet 6, le backend simple d'une appli collaborative de cuisine. La
    description sera bientot en ligne.
  </p>
  <h3>Groupomania</h3>
  Le projet 7 est un réseau social dont une démonstration sera je l'espère
  bientot en ligne également.
  <br />
  <h2>Projets personnels</h2>
  <h3><a href="https://play.jmax.dev/">JavaScript Playground</a></h3>
  <p>
    Trois petits projets d'entrainement qui m'ont permis d'apprendre ce langage.
  </p>
  <h3><a href="https://todo.jmax.dev/">Task Tracker</a></h3>
  <p>Un projet Vue3 dont j'ai réalisé le back-end.</p>
</template>

<script>
import PortFolioHeader from "@/components/PortFolioHeader.vue";
export default {
  name: "PortFolioView",
  components: {
    PortFolioHeader,
  },
};
</script>
<style scoped>
h2 {
  color: green;
}
</style>

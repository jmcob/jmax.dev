<template>
  <CVHeader />
  <h3>Bonjour ! Compétences techniques :</h3>
  <p>
    J'ai appris à coder il y a 20 ans l'<strong>HTML4</strong>, ces pages
    aujourd'hui n'existent plus !
    <br />(Et le Basic sur calculatrice scientifique)
    <br />
    En 2020, j'apprends la version 5 du markup avec le <strong>CSS</strong>.
    <br />
    En 2021, j'intègre la promotion
    <strong>Web Developer d'OpenClassrooms</strong>.
  </p>
  <h3>
    logiquement d'autres langages, <br />
    frameworks <br />
    et bases de données ont suivi...
  </h3>
  <p>
    Le Sass, <br />
    <strong>le JavaScript, Vue3, Express</strong>, <br />
    NodeJS, <strong>MongoDB, MySQL</strong> (Sequelize), <br />
    et même l'<strong>Anglais, lu écrit et parlé.</strong>
  </p>
  <router-link to="/cv2">Suite du CV</router-link>
</template>

<script>
import CVHeader from "@/components/CVHeader.vue";
export default {
  name: "CVView",
  components: {
    CVHeader,
  },
};
</script>
<style></style>

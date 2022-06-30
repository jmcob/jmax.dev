<template>
  <div class="hello">
    <CVHeader />
    <br />
    <br />
    <div class="cadre">
      <img alt="CV troisième logo" src="../assets/CV3.png" />
      <br />
      <h3>Compétences techniques :</h3>
      <p>
        J'ai appris à coder il y a 20 ans, avec l'<strong>HTML</strong>,
        <br />ainsi que le Basic sur calculatrice scientifique.
        <br />
        <br />
        En 2020, j'apprends la version 5 du markup, et le <strong>CSS</strong>.
        <br />
        L'année suivante, j'intègre la promotion
        <strong>Web Developer d'OpenClassrooms</strong>.
      </p>
      <p>
        d'autres langages, frameworks, <br />
        et bases de données ont suivi... :
      </p>
      <p>
        Le Sass, <br />
        <strong>le JavaScript, Vue.js 3, Express</strong>, <br />
        NodeJS, <strong>MongoDB, MySQL</strong> (Sequelize), <br />
        et même l'<strong>Anglais, lu écrit et parlé.</strong>
      </p>
      <br />
    </div>
    <br />
    <br />
    <br />

    <div class="cadre">
      <img alt="CV logo" src="../assets/CV.png" />
      <br />
      <h3>Etudes</h3>
      <p>
        <strong>Développeur Web / OpenClassrooms & Greta</strong> TALENCE,
        <br />
        2021/2022 <br />
        Acquisition des principaux langages du web. <br /><br />
        <strong> Evocime compétences numériques</strong> BORDEAUX,<br />
        2019/2020 <br />
        Communication et marketing digital, MS Office.
        <br />
        Stage de community management chez NovaSancO, Talence
        <br /><br />
        <strong>Université de médecine</strong> BORDEAUX, <br />
        Jusqu'en 2011, 3 années validées
      </p>
      <br />
      <h3>Emplois précédents</h3>
      <p>
        <strong>Equipier polyvalent chez Quick</strong> BORDEAUX GAMBETTA,
        <br />2012-2019 <br />
        Entretien de la salle de manière quotidienne. Prise des commandes en
        caisse.
        <br />
        <br />
        <strong>Réceptionniste en hotellerie pour Citéa</strong> BORDEAUX,
        AVIGNON ET LOURDES
        <br />
        2010
        <br />
        Accueil des clients, gestion du planning. Fermeture journalière de la
        caisse
      </p>
      <br />
    </div>
    <br />
    <br />
    <br />
    <div class="cadre">
      <img alt="CV deuxième logo" src="../assets/CV2.png" />
      <br />
      <h3>Soft skills</h3>
      <p>
        A l’écoute <br />
        Optimiste <br />
        Paisible et joyeux <br />
        Prêt à aider
      </p>
      <br />
      <h3>Supers-pouvoirs</h3>
      <p>
        <strong>Peinture abstraite</strong> depuis 2009. <br />
        <strong> Écriture</strong> depuis toujours. <br />
        <strong>Bénévole actif</strong> dans le domaine du caritatif, <br />
        dans la société Saint Vincent de Paul principalement.
      </p>
      <br />
    </div>
  </div>
  <br />
</template>

<script>
import CVHeader from "@/components/CVHeader.vue";
export default {
  name: "CVView",
  components: {
    CVHeader,
  },
  created() {
    document.title = "CV - Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>
<style scoped>
h3 {
  color: crimson;
}
</style>

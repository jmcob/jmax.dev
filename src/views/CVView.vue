<template>
  <CVHeader />
  <h3>Bonjour ! Compétences techniques :</h3>
  <p>
    J'ai appris à coder il y a 20 ans l'<strong>HTML</strong>, ces pages
    aujourd'hui n'existent plus !
    <br />(Et le Basic sur calculatrice scientifique)
    <br />
    En 2020, j'apprends la version 5 du markup avec le <strong>CSS</strong>.
    <br />
    En 2021, j'intègre la promotion
    <strong>Web Developer d'OpenClassrooms</strong>.
  </p>
  <h4>
    d'autres langages, <br />
    frameworks <br />
    et bases de données ont suivi...
  </h4>
  <p>
    Le Sass, <br />
    <strong>le JavaScript, Vue3, Express</strong>, <br />
    NodeJS, <strong>MongoDB, MySQL</strong> (Sequelize), <br />
    et même l'<strong>Anglais, lu écrit et parlé.</strong>
  </p>
  <img alt="CV logo" src="../assets/CV.png" />
  <h3>Etudes</h3>
  <p>
    <strong>Développeur Web / OpenClassrooms & Greta</strong> TALENCE,
    <br />
    2021/2022 <br />
    Acquisition des principaux langages du web. <br /><br />
    Evocime compétences numériques BORDEAUX,<br />
    2019/2020 <br />
    Communication et marketing digital, MS Office.
    <br />
    Stage de community management chez NovaSancO, Talence
    <br /><br />
    <strong>Université de médecine</strong> BORDEAUX, <br />
    Jusqu'en 2011, 3 années validées
  </p>

  <h3>Emplois précédents</h3>
  <p>
    Equipier polyvalent chez Quick BORDEAUX GAMBETTA,
    <br /><strong>2012-2019</strong> <br />
    Entretien de la salle de manière quotidienne. Prise des commandes en caisse.
    <br />

    Réceptionniste en hotellerie pour Citéa BORDEAUX, AVIGNON ET LOURDES
    <br />
    2010
    <br />
    Accueil des clients, gestion du planning. Fermeture journalière de la caisse
  </p>
  <img alt="CV deuxième logo" src="../assets/CV2.png" />
  <h3>Soft Skills</h3>
  <p>
    A l’écoute <br />
    Optimiste <br />
    Paisible et joyeux <br />
    Prêt à aider
  </p>
  <h3>Super Pouvoirs</h3>
  <p>
    <strong>Peinture abstraite</strong> depuis 2009. <br />
    <strong> Écriture</strong> depuis toujours. <br />
    <strong>Bénévole actif</strong> dans le domaine du caritatif, <br />
    dans la société Saint Vincent de Paul principalement.
  </p>
  <img alt="CV troisième logo" src="../assets/CV3.png" />
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
<style scoped>
h3 {
  color: crimson;
}
</style>

<template>
  <NavBar />
  <div class="hello">
    <CVHeader />
    <br />

    <h3><a href="#stack">Compétences techniques</a></h3>
    <h3><a href="#studies">Etudes & emplois précédents</a></h3>
    <h3><a href="#softSkills">Soft skills & Supers-pouvoirs</a></h3>
    <br /><br /><br />
    <div class="cadre">
      <div class="content">
        <a id="stack"></a>
        <div class="img">
          <img alt="CV troisième logo" src="../assets/CV3.png" />
        </div>
        <br />
        <h2>Compétences techniques :</h2>
        <div class="projects">
          <div class="card">
            <h3>Les débuts</h3>
            <p>
              <em>J'ai appris à coder :</em><br /><br />
              en 2001 avec l'<strong>HTML</strong>, <br />(ainsi que le Basic
              sur calculatrice scientifique).
              <br />
              En 2020, j'apprends la version 5 du markup, et le
              <strong>CSS</strong>. <br /><br />
              L'année suivante, j'intègre la promotion
              <strong>Web Developer d'OpenClassrooms</strong>, <br /><br />
              où <em>j'ai appris à programmer.</em>
            </p>
          </div>
          <div class="card">
            <h3>La suite des débuts</h3>
            <p>
              et les outils qui me suivent :
              <br />
              <br />
              <strong
                >JavaScript,<br />
                avec <span class="vue">Vue.js 3</span>, Vite, Nuxt,
              </strong>
              <br /><br /><strong> Express, Node.js</strong>, <br /><br />

              Git,<br /><br />
              Sass, MarkDown, VitePress <br />
              <br />

              <strong>MongoDB</strong> (Mongoose),<br />
              <strong>MySQL</strong>
              (Sequelize), <br /><br />
              et même l'<strong>Anglais, lu, écrit, et parlé.</strong>
            </p>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />

    <div class="cadre">
      <div class="content">
        <a id="studies"></a>
        <div class="img"><img alt="CV logo" src="../assets/CV.png" /></div>
        <br />
        <div class="projects">
          <div class="card">
            <h2>Etudes</h2>
            <p>
              <strong>Stage chez Géosoft</strong> MARTILLAC (33), <br />août
              2022 <br />Conception d'une page de statistiques médicales.
              <br /><br />
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
          </div>
          <div class="card">
            <h2>Emplois précédents</h2>
            <p>
              <strong>Equipier polyvalent chez Quick</strong> BORDEAUX GAMBETTA,
              <br />2012-2019 <br />
              Entretien de la salle de manière quotidienne. Prise des commandes
              en caisse.
              <br />
              <br />
              <strong>Réceptionniste en hotellerie pour Citéa</strong> BORDEAUX,
              AVIGNON ET LOURDES
              <br />
              2010
              <br />
              Accueil des clients, gestion du planning. Fermeture journalière de
              la caisse
            </p>
            <br />
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <div class="cadre">
      <div class="content">
        <a id="softSkills"></a>
        <div class="img">
          <img alt="CV deuxième logo" src="../assets/CV2.png" />
        </div>
        <br />
        <h2>Soft skills</h2>
        <p>
          A l’écoute <br />
          Optimiste <br />
          Paisible et joyeux <br />
          Prêt à aider
        </p>
        <br />
        <h2 class="powers">Supers-pouvoirs</h2>
        <p>
          <strong class="paint">Peinture abstraite</strong> depuis 2009. <br />
          <strong class="script"> Écriture</strong> depuis toujours. <br />
          <strong class="ssvp">Bénévole actif</strong> dans le domaine du
          caritatif, <br />
          dans la société Saint Vincent de Paul principalement.
        </p>
        <br />
      </div>
    </div>
  </div>
  <br />
  <NavBar />
</template>

<script>
import CVHeader from "@/components/CVHeader.vue";
import NavBar from "@/components/NavBar.vue";

export default {
  name: "CVView",
  components: {
    CVHeader,
    NavBar,
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
.powers {
  transition: 200ms;
}
.powers:hover {
  color: rgb(136, 0, 27);
  background-color: deeppink;
  cursor: pointer;
}
.powers:active {
  color: lime;
  background-color: green;
  cursor: default;
}
.paint:hover {
  color: crimson;
}
.script:hover {
  color: blue;
}
.ssvp:hover {
  color: orangered;
}
</style>

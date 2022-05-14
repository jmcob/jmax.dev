<template>
  <PortFolioHeader />
  <h2 id="piiquante-openclassrooms-web-developer-p6-2021">
    Piiquante - openClassrooms web developer P6 2021
  </h2>
  <p>
    📣 Le projet n&#39;est pas utilisable pour l&#39;utilisateur que vous êtes,
    je vous suggère de me contacter a partir de mon site web
    <a href="http://www.jmax.dev">http://www.jmax.dev</a> si vous souhaitez
    l&#39;installer et le tester. 📣
  </p>
  <h3 id="introduction">Introduction</h3>
  <p>
    Après un cours openClassrooms de Will Alexander, nous sommes propulsés dans
    le backend JS avec node.js; Nous installons tous les modules nécéssaires au
    backend dans ce repo :
  </p>
  <ol>
    <li><p>node.js tout d&#39;abord pour initialiser le repo;</p></li>
    <li><p>git, installation du repo sur github;</p></li>
    <li><p>express et mongoose pour mongoDB;</p></li>
    <li><p>helmet, dotenv, multer;</p></li>
    <li><p>bcrypt, Json Web Tokens (JWT)</p></li>
  </ol>
  <h3 id="piiquante-est-un-site-d-avis-gastronomiques">
    piiquante est un site d&#39;avis gastronomiques
  </h3>
  <p>
    Nous pouvons ici poster des sauces : une route sauce est ajoutée avec un
    controller (un middleware);
  </p>
  <p>Nous pouvons aussi y mettre des likes ou des dislikes;</p>
  <p>
    Le site web est authentifiée par utilisateur et mot de passe (route auth);
  </p>
  <h3 id="principaux-modules-courants-de-node-js-utilis-s-ici">
    Principaux modules courants de node.js utilisés ici
  </h3>
  <h3 id="node-js">Node.js</h3>
  <p>
    Nous utilisons ici node.js pour construire le backend et ainsi ajouter les
    modules nécéssaires déja cités, et décrits plus bas.
  </p>
  <p>
    Afin de lancer ce programme, si vous avez les clés du fichier .env (voire
    ensuite), vous devez disposer du frontend openclassrooms disponible sur
    <a href="https://github.com/OpenClassrooms-Student-Center/Web-Developer-P6"
      >https://github.com/OpenClassrooms-Student-Center/Web-Developer-P6</a
    >
  </p>
  <p>
    Dans un terminal dans le dossier du frontend, lancez &quot;ng serve&quot;.
  </p>
  <p>
    Dans le dossier de ce backend, dans un terminal lancez &quot;nodemon
    server&quot;, en ayant les clés stockées dans les variables
    d&#39;environnement par mon biais. Sans cela vous n&#39;aurez pas accès a
    mongoDB.
  </p>
  <h4 id="express-">Express()</h4>
  <p>
    Nous utilisons express() pour la configuration du router. Express est un
    module de node.js et un framework JS. Express permet d&#39;appliquer le CRUD
    à notre application.
  </p>
  <h4 id="mongoose">Mongoose</h4>
  <p>
    Mongoose facilite la communication avec une base de donnée mongoDB ;
    mongoose est conçu pour node.js dont il est un module. Créer un schéma,
    appliquer le CRUD avec notre base de donnée, tout est possible avec
    Mongoose. Utilisation de dotenv pour securiser l&#39;acces a mongoDB.
  </p>
  <h4 id="multer">Multer</h4>
  <p>
    Multer récupère et stocke sur le serveur les fichiers envoyés par les
    utilisateurs. Ici, il est configuré de manière à stocker dans le dossier
    images/ les images de sauces proposées par chaque utilisateur.
  </p>
  <h3 id="modules-de-s-curit-sur-node-js">modules de sécurité sur node.js</h3>
  <h4 id="dotenv">Dotenv</h4>
  <p>
    Dotenv permet de travailler avec des variables d&#39;environnement et
    sécuriser les mots de passe d&#39;un backend node.js.
  </p>
  <p>
    La documentation de dotenv se trouve ici :
    <a href="https://www.npmjs.com/package/dotenv"
      >https://www.npmjs.com/package/dotenv</a
    >
    (en anglais).
  </p>
  <p>
    Succintement, il vous faudra installer dotenv sur le projet, puis definir
    une constante qui vaudra [require(&#39;dotenv&#39;).config()] dans le
    fichier app.js. Un fichier nommé tout simplement [.env] sans les crochets
    stockera les données sensibles qui ne peuvent pas être partagées
    publiquement sur GitHub par exemple. Vous avez un exemple de ces données sur
    .env.example dans ce projet.
  </p>
  <p>
    Ce fichier pourra tout de même etre envoyé sur les serveurs
    d&#39;hébergement de manière sécurisée, comme Heroku ou Google Workspace.
  </p>
  <h4 id="helmet">Helmet</h4>
  <p>
    Helmet permet a l&#39;application de respecter les recommandations OWASP.
  </p>
  <h4 id="jwt-json-web-tokens">JWT : JSON Web Tokens</h4>
  <p>
    JWT est un module node.js qui permet de crypter les tokens
    d&#39;authentification envoyés au client pour authentifier leur session,
    selon une clé définie par le développeur. Cette clé est généralement stockée
    dans le fichier .env.
  </p>
  <h4 id="bcrypt">bcrypt</h4>
  <p>
    Bcrypt permet de faire un &quot;hash&quot; du mot de passe du client, de
    maniere a ce que cette chaine de caractère ne soit pas stockées coté serveur
    (mais seulement ce hash). Ainsi lorsque l&#39;utilisateur se connecte avec
    son mot de passe, ce mot de passe est de nouveau haché et comparé au hash du
    serveur. Si les deux hash viennent du même mot de passe, les hash se
    reconnaitront.
  </p>
  <h4 id="email-validator-et-password-validator">
    Email-validator et password-validator
  </h4>
  <p>
    <a href="https://github.com/manishsaraan/email-validator"
      >https://github.com/manishsaraan/email-validator</a
    >
    pour email-validator et
    <a href="https://github.com/tarunbatra/password-validator"
      >https://github.com/tarunbatra/password-validator</a
    >
    pour password-validator. Les détails de l&#39;implémentation de ces modules
    sont sur leur page github.
  </p>
  <p>Merci de m&#39;avoir lu.</p>
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

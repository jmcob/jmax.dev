<template>
  <div class="container">
    <h1>Me contacter</h1>
    <p>
      Si vous désirez me contacter, présentez-vous dans un bref message, en
      expliquant également le but de votre requête. <br />Je vous remercie pour
      l'intérêt que vous portez à mon travail.
    </p>

    <form ref="form" @submit.prevent="sendEmail">
      <label>Nom</label>
      <input type="text" v-model="name" name="name" placeholder="Votre nom" />
      <label>Email</label>
      <input
        type="email"
        v-model="email"
        name="email"
        placeholder="Votre e-mail"
      />
      <label>Message</label>
      <textarea
        name="message"
        v-model="message"
        cols="30"
        rows="5"
        placeholder="Message"
      >
      </textarea>

      <input type="submit" :value="send" />
    </form>
  </div>
</template>

<script>
import emailjs from "emailjs-com";
export default {
  name: "ContactForm",
  data() {
    return {
      name: "",
      email: "",
      message: "",
      send: "Envoyer",
      sent: false,
    };
  },
  methods: {
    sendEmail(e) {
      try {
        emailjs.sendForm(
          "service_ym069uf",
          "template_ic7pb7i",
          e.target,
          "8teXph77JJiHSkBju",
          {
            name: this.name,
            email: this.email,
            message: this.message,
          }
        );
      } catch (error) {
        console.log({ error });
      }
      // Reset form field
      this.name = "";
      this.email = "";
      this.message = "";
      this.send = "Merci pour votre message";
      this.sent = true;
      let button = document.getElementsByTagName("input")[2];
      button.style.backgroundColor = "#4caf50";
    },
  },
};
</script>

<style scoped>
* {
  box-sizing: border-box;
}

.container {
  display: block;
  margin: auto;
  text-align: center;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
  width: 50%;
}

label {
  float: left;
}

input[type="text"],
[type="email"],
textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type="submit"] {
  background-color: crimson;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type="submit"]:hover {
  background-color: red;
}
</style>

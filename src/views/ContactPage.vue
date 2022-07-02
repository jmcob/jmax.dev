<script>
import ContactForm from "@/components/ContactForm.vue";
import NavBar from "@/components/NavBar.vue";

export default {
  name: "ContactPage",
  components: {
    ContactForm,
    NavBar,
  },
  created() {
    document.title = "Contact - Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>

<template>
  <NavBar />
  <ContactForm />
</template>

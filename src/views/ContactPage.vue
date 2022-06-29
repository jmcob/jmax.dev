<script>
import ContactForm from "@/components/ContactForm.vue";

export default {
  name: "ContactPage",
  components: {
    ContactForm,
  },
  created() {
    document.title = "Contact - Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>

<template>
  <ContactForm />
</template>

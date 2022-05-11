<template>
  <h3 @click="show = !show">{{ title }}</h3>
  <p v-if="show">{{ content }}</p>
</template>

<script>
export default {
  name: "CVItem",
  props: {
    title: String,
    content: String,
  },
  data() {
    return {
      show: false,
    };
  },
};
</script>

<style>
h3 {
  cursor: pointer;
}
</style>

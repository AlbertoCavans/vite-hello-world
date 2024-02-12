<script>
import AppTitle from "../components/AppTitle.vue";

export default {
  data() {
    return {
      title: "Titolo finto, perché il titolo vero sarà nel componente AppTitle",
    };
  },

  methods: {},

  components: {
    AppTitle: AppTitle,
  },
};
</script>

<template>
  <h6 class="font-style">{{ title }}</h6>
  <AppTitle></AppTitle>
</template>

<style>
.font-style {
  font-style: italic;
}
</style>

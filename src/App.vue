<script>
export default {
  data() {
    return {
      title: "Titolo finto, perché il titolo vero sarà nel componente AppTitle",
    };
  },

  methods: {},
};
</script>

<template>
  <h6 class="font-style">{{ title }}</h6>
</template>

<style>
.font-style {
  font-style: italic;
}
</style>

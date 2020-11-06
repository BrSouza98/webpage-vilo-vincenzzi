<template>
  <div>
    <carousel></carousel>
    <conteudo></conteudo>
    <footer></footer>
  </div>
</template>

<script>
import migalhaVue from "../components/migalha.vue";

export default {
  components: {
    migalhaComponent: migalhaVue,
  },

  data() {
    return {
      migalha: "d-none",
    };
  },
};
</script>

<style scoped>
</style>
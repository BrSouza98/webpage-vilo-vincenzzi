<template>
  <b-card-group deck>
    <b-card
      bg-variant="info"
      text-variant="white"
      class="text-center shadow-sm rounded"
      :header="titulo"
      :alt="alt"
    >
      <b-card-text
        >{{texto}}</b-card-text
      >
    </b-card>
  </b-card-group>
</template>

<script>
export default {
  name: "card",

  props: ["titulo", "alt", "texto"],

  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
</style>

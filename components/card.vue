<template>
  <b-card-group deck>
    <b-card
      bg-variant="info"
      text-variant="white"
      class="text-center shadow-sm rounded"
      :header="titulo"
      :alt="alt"
    >
      <b-card-text>{{ texto }}</b-card-text>
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
.card-header {
  background-color: rgba(0, 0, 0, 0.363);
  font-weight: bolder;
}

.card-deck .card {
  min-height: 350px;
}
</style>

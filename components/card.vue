<template>
  <div id="app" class="cardConfig">
    <b-card-group>
      <b-card
        :img-src="imagem"
        :header="titulo"
        :alt="alt"
      >
        <b-card-text class="conteudoCard">{{ texto }}</b-card-text>
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
export default {
  name: "card",

  props: ["titulo", "alt", "texto", "imagem"],

  data() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
.card-header {
  padding: 0.75rem 1.25rem;
  margin-bottom: 0;
  background-color: #3a3a3a;
  border-bottom: 1px solid rgba(0, 0, 0, 0.125);
  color: rgb(211, 211, 211);
  font-weight: bold;
  display: flex;
  justify-content: center;
}

.cardConfig {
  margin: 20px;
}

.card-img,
.card-img-bottom {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
</style>

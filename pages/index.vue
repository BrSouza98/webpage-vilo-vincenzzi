<template>
  <div>
    <carrosel></carrosel>
    <h1>Bem-vindo a minha primeira página vue!</h1>

    <b-row cols="3">
      <b-col>
        <card
          titulo="Titulo ok"
          alt="card de apresentacao"
          texto="texto padrão"
        ></card>
      </b-col>

      <b-col>
        <card></card>
      </b-col>

      <b-col>
        <card></card>
      </b-col>
    </b-row>
  </div>
</template>

<script>
import cardVue from "../components/card.vue";

export default {
  components: {
    card: cardVue
  }
};
</script>

<style></style>

<template>
  <div>
    <carrosel></carrosel>
    <b-container fluid>
      <b-row class="d-flex justify-content-center">
        <h1>Bem-vindo a Vilo Vincenzzi!</h1>
      </b-row>
    </b-container>

    <b-container fluid>
      <b-row cols="3">
        <b-col>
          <card
            titulo="Titulo ok"
            alt="card de apresentacao"
            texto="texto padrão"
          ></card>
        </b-col>

        <b-col>
          <card
            titulo="Titulo ok"
            alt="card de apresentacao"
            texto="texto padrão"
          ></card>
        </b-col>

        <b-col>
          <card
            titulo="Titulo ok"
            alt="card de apresentacao"
            texto="texto padrão"
          ></card>
        </b-col>
      </b-row>
    </b-container>
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

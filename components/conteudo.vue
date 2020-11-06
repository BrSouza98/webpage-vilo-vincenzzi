<template>
  <main>
    <div>
      <div>
        <h1>Bem-vindo ao Vilo Vincenzzi!</h1>
      </div>

      <b-container>
        <b-row cols="1" cols-lg="3">
          <b-col>
            <card
              titulo="Essa escolinha é pika!"
              imagem-alt="Descrição do card"
              texto="Lorem ipsum dolor sit amet consectetur adipisicing elit."
              class="animate__animated animate__fadeInLeft"
            ></card>
          </b-col>

          <b-col>
            <card
              titulo="Essa escolinha é pika!"
              imagem-alt="Descrição do card"
              texto="Lorem ipsum dolor sit amet consectetur adipisicing elit."
              class="animate__backInUp"
            ></card>
          </b-col>

          <b-col>
            <card
              titulo="Essa escolinha é pika!"
              imagem-alt="Descrição do card"
              texto="Lorem ipsum dolor sit amet consectetur adipisicing elit."
              class="animate__backInRight"
            ></card>
          </b-col>
        </b-row>
      </b-container>
    </div>

  </main>
</template>

<script>
import cardVue from "./card.vue";
import migalhaVue from "./migalha.vue";
import Vue from 'vue'
import { BootstrapVue, BootstrapVueIcons } from 'bootstrap-vue'

Vue.use(BootstrapVue)
Vue.use(BootstrapVueIcons)

export default {
  components: {
    card: cardVue,
    migalha: migalhaVue,
  },
  data() {
    return {
      migalha: false,
    };
  },
};
</script>

<style scoped>
</style>
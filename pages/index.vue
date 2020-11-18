<template>
  <div class="corpadrao1">
    <gif class="p-0 m-0" />
    <!-- Inicio apresentacao -->
    <img src="~/assets/png1.png" alt="" class="bannersConteudo" />

    <cardApresentation />

    <!-- Fim apresentação -->

    <!-- Inicio blog -->
    <img src="~/assets/png2.png" alt="" class="bannersConteudo" />

    <cardNoticias />

    <!-- Fim blog -->
  </div>
</template>

<script>
import CardBlog from "../components/card-blog.vue";
import cardVue from "../components/card.vue";
import CardApresentation from "../components/cardApresentation.vue";
import CardNoticias from "../components/cardNoticias.vue";
import Gif from "../components/gif.vue";

export default {
  components: {
    card: cardVue,
    CardApresentation,
    CardBlog,
    CardNoticias,
  },
  Gif,
};
</script>

<style scoped>
.card-header {
  padding: 0.75rem 1.25rem;
  margin-bottom: 0;
  font-weight: bold;
  display: flex;
  justify-content: space-around;
}

.card-header1 {
  padding: 1.75rem 1.25rem;
  margin-bottom: 0;
  font-weight: bold;
  display: flex;
  justify-content: space-evenly;
}

.branco {
  background-color: white;
}
.imgtamanho {
  height: 300px;
}
.imgteste {
  padding: 0.75rem 1.25rem;
  margin-bottom: 0;
  font-weight: bold;
  display: flex;
  justify-content: space-around;
}
.corpreta {
  color: black;
}
.updown {
  margin-top: 40px;
  margin-bottom: 40px;
}

.bannersConteudo {
  width: 100%;
  padding: 0;
  margin: 0;
  height: 500px;
}
</style>

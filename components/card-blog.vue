<template>
  <div>
    <b-card
      :title="titulo"
      :img-src="require(`@/assets/${imagem}.png`)"
      img-alt="ImagemAlt"
      img-top
      tag="article"
      class="my-2"
    >
      <b-card-text>
        {{texto}}
      </b-card-text>

      <b-button href="https://wordpress.com/page/vilovicenzzi.wordpress.com/7" target="_blank" variant="primary">Ler</b-button>
    </b-card>
  </div>
</template>

<script>
export default {
  name: "card-blog",
  props: ['titulo', 'texto', 'imagem'],
};
</script>

<style scoped>
  img{
    max-height: 200px;
  }
</style>

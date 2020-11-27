<template>
  <div class="espacoclasse">
    <b-card
      :title="titulo"
      img-src="~/assets/emebfoto.png"
      img-alt="ImagemAlt"
      img-top
      tag="article"
      style="max-width: 20rem"
      class="mb-2"
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

<style>
.corpreta {
  color: black;
}

.espacobotao {
  margin-bottom: 20px;
}
.espacoclasse {
  margin-top: 40px;
}
</style>

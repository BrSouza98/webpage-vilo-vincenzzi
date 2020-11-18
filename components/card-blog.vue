<template>
  <div>
    <b-card :title="titulo" :sub-title="subTitulo">
      <b-card-text>
        {{texto}}
      </b-card-text>

      <b-button variant="primary">Acessar Matéria</b-button>
      <b-button variant="outline-primary">Visitar Blog</b-button>
    </b-card>
  </div>
</template>

<script>
export default {
    name: 'card-blog',
    props:['titulo', 'subTitulo', 'texto']
};
</script>

<style></style>

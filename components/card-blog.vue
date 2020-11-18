<template>
  <div>
    <b-card class="espacoclasse" :title="titulo" :sub-title="subTitulo">
      <b-card-text>
        {{texto}}
      </b-card-text>

      <b-button class="espacobotao" variant="primary"><a class="corpreta" href="https://vilovicenzzi.wordpress.com/2020/10/12/nosso-trabalho-em-plena-pandemia/" target="_blank">Acessar materia</a></b-button>
      <b-button class="espacobotao" variant="outline-primary"><a class="corpreta" href="https://vilovicenzzi.wordpress.com/" target="_blank">Acessar Blog completo</a></b-button>
    </b-card>
  </div>
</template>

<script>
export default {
    name: 'card-blog',
    props:['titulo', 'subTitulo', 'texto']
};
</script>

<style>
.corpreta{
  color: black;
}

.espacobotao{
  margin-bottom: 20px;
}
.espacoclasse{
  margin-top: 40px;
}
</style>

<template>
      <nav aria-label="breadcrumb" :v-show="vizualizar">
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="/">Página inicial</a></li>
        <li class="breadcrumb-item active" aria-current="page">Contato</li>
      </ol>
    </nav>
</template>

<script>
export default {
    name: 'migalha',

  

    data(){
      return{
        vizualizar: false,
      }
    }
}
</script>

<style scoped>
  .breadcrumb{
    background-color: white;
  }
</style>
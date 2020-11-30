<template>
  <div id="card" class="shadow">
    <b-container id="my-card">
      <div class="w-100 d-flex justify-content-center">
        <img :src="require(`~/assets/ui/${imagem}.png`)" alt="" />
      </div>
      <div>
        <h3 class="text-center w-100">{{ titulo }}</h3>
        <p class="text-justify">{{ texto }}</p>
      </div>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "card",

  props: ["titulo", "alt", "texto", "imagem"],
};
</script>

<style lang="scss" scoped>
$preto-opaco: rgba(0, 0, 0, 0.363);
$azul: #3ea4bf;

*{
  box-sizing: border-box;
}

img {
  max-height: 300px;
}

h3 {
  border-bottom: 1px solid $preto-opaco;
  height: 50px;
  font-size: 30px;
  color: $azul;
  font-weight: bold;
}

p {
  font-size: 17px;
  padding: 15px;
}

#my-card {
  border: 1px solid rgba(9, 90, 196, 0.288);
  border-radius: 15px;
  min-height: 600px;
}

</style>

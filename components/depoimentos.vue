<template>
<div>
    <div class="depoimentos">
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Slide with blank fluid image to maintain slide aspect ratio -->
    </b-carousel>
  </div>
</div>

</template>

<script>
export default {};
</script>

<style scoped>
    .depoimentos{
        height: 100px;
        box-sizing: border-box;
    }
</style>
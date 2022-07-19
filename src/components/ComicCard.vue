<template>
  <div class="comic-card">
    <img :src="cover" :alt="series" />
    <h5 class="fw-bold text-light mt-3 fs-6">{{series}}</h5>
  </div>
</template>

<script>
export default {
  props:{
    cover:String,
    price:String,
    series:String,
    type: String
  }
};
  
</script>

<style lang="scss" scoped>
  .comic-card {
    width: calc(100% / 6);
    padding: 1rem;

      img{
        height: 12rem;
        width: 12rem;
        object-fit: cover;
        object-position: top;
      }
  }
</style>
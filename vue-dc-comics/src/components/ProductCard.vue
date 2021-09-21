<template>
  <div class="product-card">
      <div>
 <img :src="card.thumb" :alt="card.series">
     <p>{{card.series}}</p>
      </div>
   
  </div>
</template>

<script>
export default {
  name: 'ProductCard',
  props: ['card']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .product-card {
    margin: 10px;
    img {
      width: 50%;
    }

    p {
      max-width: 100px;
    }
  }

</style>
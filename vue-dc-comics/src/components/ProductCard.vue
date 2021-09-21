<template>
  <div class="product-card">
  
    <h2>Cottura: {{ card.cottura }} minuti</h2>
    <img :src="card.src" :alt="card.titolo">
      <p>{{ card.titolo }}</p>
    
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

</style>
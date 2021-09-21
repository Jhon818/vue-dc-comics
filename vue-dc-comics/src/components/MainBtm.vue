<template>
  <div>
      <MainBtm 
       v-for="(img, index) in imgs" 
      :key="index"
      :img="img"
      />
  </div>
</template>

<script>

export default {
 name: 'MainBtm',
 
//  data() {
//     return {
//       imgs: img
//     }
//   }
}
</script>

<style lang="scss">

div.banner-main-btm {
   height: 5vh;
   background: blue;
}
</style>
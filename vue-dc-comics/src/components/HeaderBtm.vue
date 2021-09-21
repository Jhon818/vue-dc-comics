<template>
  <div class="banner-header-btm">
      <img src="@/assets/img/jumbotron.jpg">
      <div class="current-series">
          <span>current series</span>
      </div>
  </div>
</template>

<script>
export default {
 name: 'HeaderBtm',
}
</script>

<style lang="scss">

div.banner-header-btm {
   width: 100%;
   height: 300px;
   z-index: -1;
   position: relative;
   

    img {
        width: 100%;
        transform-origin: center;
    }
}

.current-series {
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    width: 10vw;
    height: 35px;
    background: blue;
    color: white;
    padding: 10px;
    text-transform: uppercase;

    span{
        width: 100%;
    }
}
</style>
<template>
  <div id="app">
    <Header />

    <HeaderBtm />  
    
      <Products />
      <MainBtm />
    

    <Footer />
  </div>
</template>

<script>
// La @ ci porta direttamente nella cartella src del progetto
    import Header from '@/components/Header.vue'
    import HeaderBtm from '@/components/HeaderBtm.vue'
    import MainBtm from '@/components/MainBtm.vue'
    import Footer from '@/components/Footer.vue'
    import Products from '@/components/Products.vue'

    export default {
      name: 'App',
      components: {
        Header,
        HeaderBtm,
        Products,
        MainBtm,
        Footer
      }
    }
</script>
           

      <style lang="scss">
      @import "./style/general";
      @import "./style/vars";
      h1,
      h2,
      h3 {
        color: $primary;
      }
      </style>
<template>
  <div id="app">
    <Header />

    
    
      <Main />
    
    

    <Footer />
  </div>
</template>

<script>
// La @ ci porta direttamente nella cartella src del progetto
    import Header from '@/components/Header.vue'
    import Main from '@/components/Main.vue'
    import Footer from '@/components/Footer.vue'
    export default {
      name: 'App',
      components: {
        Header,
        Main,
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

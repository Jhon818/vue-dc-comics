<template>
  <header>
    <a href="/" class="brand">
      <img src="@/assets/img/dc-logo.png" alt="">
    </a>

    <nav>
      <ul>
          <li v-for="(link,index) in links" :key="index">
              <span>{{link.text}}
                  <div :class="(link.current) ? 'active' : null" href="link.url"></div>
              </span>
         </li>
      </ul>
    </nav>
  </header>
</template>

<script>
    import * as Links from '@/assets/data/Links.js'
    export default {
    name: 'Header',
  
  data() {
    return {
      links: Links.headerLinks
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import "../style/mixins";
  @import "../style/vars";
  @import "../style/general";

  header {
     display: flex;
     background: white;
     align-items: center;
     justify-content: space-around;

   li {
      display: inline-flex;
      margin: 20px;
      text-transform: uppercase;
      cursor: pointer;
      position: relative;
      height: 50px;
   }

   li:hover {
       color: $primary;

        span > div {
        background-color: #0282F9;
        bottom: 0;
        content: '';
        display: block;
        height: 5px;
        position: absolute;
        -webkit-transform: scaleY(0);
        transform: scaleY(0);
        -webkit-transform-origin: bottom;
        transform-origin: bottom;
        transition-duration: .3s;
        transition-property: -webkit-transform;
        transition-property: transform;
        transition-property: transform,-webkit-transform;
        transition-timing-function: ease-in-out;
        width: 100%;
   }

   }

  .active {
    display: block;
  }
    img {
       width: 4rem;
   }

   nav {
       display: flex;
       font-size: 0.8em;
   }
  
  }
</style>

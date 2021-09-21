<template>
  <div class="container">
    <div class="banner-img">
      <img src="@/assets/img/footer-bg.jpg" alt="">
    </div>
      <div class="socials">
        <button>
SIGN UP NOW
        </button>
        <div>
          <span>FOLLOW US</span>
          <ul>
            <li></li>
          </ul>
        </div>
      </div>
      <div>
 <img id="img-hidden" src="@/assets/img/dc-logo-bg.png" alt="">
      </div>
  
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.container {
  height: 50vh;
  width: 100%;
  position: relative;

  .banner-img {
    height: 100%;
    width: 100%;
    
  }
  img {
    height: 100%;
    width: 100%;
  }

  .socials {
    color: blue;
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 10vh;
    background: grey;
  }

  button {
    height: 30px;
    width: 100px;
    background: grey;
    border: 1px solid blue;
    color: white;
  }

  #img-hidden {
    position: absolute;
    top: 0;
    right: 20%;
    width: 35%;
  }
}
</style>
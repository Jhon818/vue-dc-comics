<template>
  <div class="container">
    <div class="footer-list">
 <ul>
      <li>DC COMICS</li>
      <li>Characters</li>
      <li>Comics</li>
      <li>Movies</li>
      <li>Tv</li>
      <li>Games</li>
      <li>Videos</li>
      <li>News</li>
    </ul>
      <ul>
      <li>DC</li>
      <li>Characters</li>
      <li>Comics</li>
      <li>Movies</li>
      <li>Tv</li>
      <li>Games</li>
      <li>Videos</li>
      <li>News</li>
    </ul>
      <ul>
      <li>SITES</li>
       <li>Characters</li>
      <li>Comics</li>
      <li>Movies</li>
      <li>Tv</li>
      <li>Games</li>
      <li>Videos</li>
      <li>News</li>
 </ul>

  <ul>
      <li>SHOP</li>
       <li>Characters</li>
      <li>Comics</li>
 </ul>
    </div>
   
    <div class="banner-img">
      <img src="@/assets/img/footer-bg.jpg" alt="">
    </div>
      <div class="socials">
        <button>
SIGN UP NOW
        </button>
        <div class="footer-social">
          <div class="center-flex">
            <span>FOLLOW US</span>
            <span><img src="@/assets/img/footer-facebook.png" alt=""></span>
            <span><img src="@/assets/img/footer-periscope.png" alt=""></span>
            <span><img src="@/assets/img/footer-pinterest.png" alt=""></span>
            <span><img src="@/assets/img/footer-twitter.png" alt=""></span>
          </div>
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

  .footer-list {
    width: 50%;
    position: absolute;
    left: 5%;
  }

  ul {
    display: inline-block;
    width: 20%;
    background:none;
  }

  li:first-child {
    padding-bottom: 3px;
    color: white;
  }
  li {
    display: flex;
    padding: 2px;
    color: grey;
  }

  .socials {
    display: flex;
    align-items: center;
    background: rgb(95, 90, 90);
    justify-content: space-around;
  }

  .banner-img {
    height: 100%;
    width: 100%;
    
  }
  img {
    height: 100%;
    width: 100%;
  }

  .footer-social {
    color: blue;
    display: inline-block;
   

    div span > img{
        width: 2em;
        color: blue;
        padding: 20px;
    }

    .center-flex {
      display: flex;
      align-items: center;
    }
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
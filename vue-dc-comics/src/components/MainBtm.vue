<template>
 <div class="comics-banner">
    <ul>
            <li><img src="@/assets/img/buy-comics-digital-comics.png" alt="">DIGITAL COMICS</li>
            <li><img src="@/assets/img/buy-comics-merchandise.png" alt="">DC MERCHANDISE</li>
            <li><img src="@/assets/img/buy-comics-shop-locator.png" alt="">SUBSCRIPTIONS</li>
            <li><img src="@/assets/img/buy-comics-subscriptions.png" alt="">COMIC SHOP LOCATOR</li>
   </ul>
      </div>  

</template>

<script>

export default {
 name: 'MainBtm',
}
</script>

<style lang="scss">

div.comics-banner {
  display: flex;
  justify-content: center;
  background: blue;
  color: white;
}
div > ul {
  display: inline-flex;
  justify-content: center;
  width: 100%;


li {
  display: flex;
  align-items: center;
  list-style: none;
  padding: 3em;
}

img {
  width: 3em;
  padding: 1em;
}

}
</style>
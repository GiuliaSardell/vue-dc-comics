<template>
  <div class="options">
    <div class="container">
      <a href="#">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <span>Digital Comics</span>
      </a>
      <a href="#">
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <span>DC Merchandise</span>
      </a>
      <a href="#">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <span>Subscriptions</span>
      </a>
      <a href="#">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <span>Comic Shop Locator</span>
      </a>
      <a href="#">
        <img src="../assets/img/buy-dc-power-visa.svg"  alt="">
        <span>DC Power Visa</span>
      </a>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'Options'
}
</script>

<style lang="scss">

@import "../assets/style/vars.scss";

.options{
  background-color: $primary-color;
  .container{
    padding: 0 20px;
  }
  img{
    width: 40px;
    vertical-align: middle;
  }
  a{
    margin: 20px 0;
  }
  span{
    text-transform: uppercase;
    font-size: 12px;
    color:white;
    margin: 0 10px;
  }
}

</style>
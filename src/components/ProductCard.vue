<template>
  <div class="product-card">
    <img :src="productImage" :alt="productName">
    <h3>{{productName}}</h3>

    
  </div>
</template>

<script>
export default {
  name: 'ProductCard',
  props:{
    productName: String,
    productImage: String,
  }

}

</script>

<style lang="scss">
@import "../assets/style/vars.scss";
@import "../assets/style/generals.scss";

.product-card{
  // flex-basis: 12%;
  width: 150px;
  height: 150px;
  margin: 40px 10px;
  img{
    height: 100%;
    width: 100%;
    overflow: hidden;
  }

  h3{
    color: white;
    font-size: 14px;
    margin-bottom: 30px;
  }

  
}


</style>
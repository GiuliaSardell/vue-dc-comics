<template>
  <div class="product-card">
    <div class="container-card">
      <img :src="productImage" :alt="productName">
      
    </div>
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
  width: calc(100% / 6 - 40px);
  // padding-top: calc(100% / 6 - 20px);
  // height: 150px;
  // margin: 40px 10px;
  margin: 25px 20px;
  cursor: pointer;
 
  .container-card{
    width: 100%;
    height: 0;
    padding-top: 100%;
    position: relative;
    overflow: hidden;
    

  }
  img{
    // height: 100%;
    width: 100%;
    display: block;
    position: absolute;
    top: 0;
    left: 0;
  }

  h3{
    color: white;
    font-size: 14px;
    margin: 20px 0;
  }

  
}


</style>
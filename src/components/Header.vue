<template>
  <header>
    <div class="container">
      <a href="#">
        <img src="../assets/img/dc-logo.png" alt="logo">
      </a>
      <nav>
        <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIE</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEO</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
        </ul>
      </nav>
    </div>
   
    
  </header>
</template>

<script>
export default {
  name: 'Header'

}
</script>

<style lang="scss">
header{
  background-color: red;
  

  a img{
    width: 80px;
    margin: 10px;
  }
  ul li{
    list-style: none;
    margin: 0 10px;
    display: inline-block;
    font-size: 12px;
    font-weight: bold;
    a{
      text-decoration: none;
      color: black;
      &:hover{
        color: #0C7CEC;
        border-bottom: 5px solid #0C7CEC;
        padding-bottom: 38px;
      }
    }
  }
  
}



</style>
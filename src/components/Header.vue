<template>
  <header>
    <div class="container">
      <a href="#">
        <img src="../assets/img/dc-logo.png" alt="logo">
      </a>
      <nav>
        <ul>
          <li v-for="(item,index) in links" :key="index">
            <a :href="item.url">{{item.text}}</a>
          </li>
          <!-- <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIE</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEO</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li> -->
        </ul>
      </nav>
    </div>
   
    
  </header>
</template>

<script>
export default {
  name: 'Header',
  data(){ //data diventa una funzione che ritorna un oggetto
    return{
          // i data vengono inseriti qui
      links:[
        {
          url: '/',
          text: 'characters',
          class: false
        },
        {
          url: '/',
          text: 'comics',
          class: false
        },
        {
          url: '/',
          text: 'movie',
          class: false
        },
        {
          url: '/',
          text: 'tv',
          class: true
        },
        {
          url: '/',
          text: 'Games',
          class: false
        },
        {
          url: '/',
          text: 'collectibles',
          class: false
        },
        {
          url: '/',
          text: 'video',
          class: false
        },
        {
          url: '/',
          text: 'fans',
          class: false
        },
        {
          url: '/',
          text: 'news',
          class: false
        },
        {
          url: '/',
          text: 'shop',
          class: false
        },
      ]
    }
  }

}
</script>

<style lang="scss">

@import "../assets/style/vars.scss";

header{
  
  a img{
    width: 80px;
    margin: 10px 0;
  }
  ul li{
    // list-style: none;
    // display: inline-block;
    margin: 0 10px;
    font-size: 12px;
    font-weight: bold;
    a{
      // text-decoration: none;
      text-transform: uppercase;
      color: black;
      &:hover, &active{
        color: $primary-color;
        border-bottom: 5px solid $primary-color;
        padding-bottom: 38px;
      }
    }
  }
  
}



</style>
<template>
  <footer> 
    <div class="footer-top">
      <div class="container">
        <div class="column">
          <ul>
            <li><span>dc comics</span></li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <ul>
            <li><span>shop</span></li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>

        <ul>
          <li><span>dc comics</span></li>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
        </ul>

        <ul>
          <li><span>shop</span></li>
          <li><a href="#">Shop DC</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
        </ul>

        <div class="sfondo">

        </div>
        <!-- <img src="../assets/img/dc-logo-bg.png" alt=""> -->


     


      </div>

    </div>
    <div class="footer-bottom">
      <div class="container">
        <button>Sign-up now</button>
        <nav>
          <span>follow us</span>
          <img src="../assets/img/footer-facebook.png" alt="">
          <img src="../assets/img/footer-facebook.png" alt="">
          <img src="../assets/img/footer-facebook.png" alt="">
          <img src="../assets/img/footer-facebook.png" alt="">
          <img src="../assets/img/footer-facebook.png" alt="">
        </nav>

      </div>
    </div>

  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>



<style lang="scss">

@import "../assets/style/vars.scss";

footer{
  .footer-top{
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;

    .container{
      align-items: stretch;

      .sfondo{
        background-image: url(../assets/img/dc-logo-bg.png);
        width: 450px;
        background-size: cover;
      }
      
      .column{
        display: flex;
        flex-direction: column;
      }

      img{
        overflow: hidden;
      }
      
      ul{
        display: flex;
        flex-direction: column ; 
        margin: 10px 20px;
        li{
          &:first-child {
            margin: 20px 0;
          }
          margin: 3px 0;
        }
          span{
          text-transform: uppercase;
          font-size: 16px;
          font-weight: bold;
          color: white;
          }
          
          a{
            color: #7F7F7F;
            &:hover{
            color: white;
            }
          }
          
      }
     
    }
  }
  
  .footer-bottom{
    background-color: #303030;
    .container{
      button{
        padding: 10px;
        background-color: #303030;
        border: 1px solid $primary-color;
        color: white;
        text-transform: uppercase;
        margin: 30px 0;
        cursor: pointer;
          &:hover{
            background-color: $primary-color;
          }
      }
      span{
        color: $primary-color;
        text-transform: uppercase;
        vertical-align: middle;
        margin: 0 10px;
      }
      img{
        vertical-align: middle;
        margin: 0 5px;
        cursor: pointer;
      }
      
    } 
  }
}

</style>
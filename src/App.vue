<template>
  <div>
    <Header />
    <Jumbo />
    <Main />
    <Options />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Options from './components/Options.vue';
import Footer from './components/Footer.vue';
import Jumbo from './components/Jumbo.vue';


export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Main,
    Options,
    Footer
  }
}
</script>

<style lang="scss">
//importo uno stile che è i locale
@import './assets/style/generals.scss'


</style>

<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
    <div id="bottom"></div>
  </div>
  
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
@import '../node_modules/fontawesome-free/css/all.css';
@import "./components/style/General";

  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }
    #bottom {
        width: 100%;
        height: 50px;
        background-color: $orange;
        margin: 0;
    }
</style>

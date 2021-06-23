<template>
  <div id="app">
    <Header />
    <Main />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main
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
</style>

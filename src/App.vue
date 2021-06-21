<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Header />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Libre+Baskerville:wght@400;700&family=Noto+Serif&display=swap');
  //font-family: 'Libre Baskerville', serif;
  @import url('https://fonts.googleapis.com/css2?family=Lato:wght@700&family=Libre+Baskerville:wght@400;700&family=Noto+Serif&display=swap'); //font-family: 'Lato', sans-serif;


  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }
</style>

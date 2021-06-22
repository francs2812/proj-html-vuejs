<template>
  <div id="app">
    <Header />
    <Specialties />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Specialties from './components/Specialties.vue'

export default {
  name: 'App',
  components: {
    Header,
    Specialties
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

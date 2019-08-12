<template>
  <div id="app">
    <Splash SplashText="Centerville Student Council"/>
    <vue-position-sticky>
      <Header class="sticky"/>
    </vue-position-sticky>
    <Article/>
    <Article/>
    <Article/>
    <Article/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Splash from './components/Splash.vue'
import Article from './components/Article.vue'

export default {
  name: 'app',
  components: {
    Header,
    Splash,
    Article
  }
}
</script>

<style>
#app {
  margin: 0px;
  padding: 0px;
  width: 100%;
  height: 100%;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>

<template>
  <div id="app">
    <MyHeader/>
    <MySection/>
    <MyMain/>
    <MyFooter/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'
import MySection from './components/MySection.vue'




export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter,
    MySection
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  max-height: 100vh;
}
</style>

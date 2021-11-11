<template>
  <div id="app">
    <HeaderSite />
    
  </div>
</template>

<script>
import HeaderSite from './components/HeaderSite.vue'
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HeaderSite
   
  }
}
</script>

<style lang="scss">

*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app{
  font-family: Arial, Helvetica, sans-serif;
}

</style>

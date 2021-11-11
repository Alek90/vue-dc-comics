<template>
  <div id="app">
    <HeaderSite />
    <MainSite />
    
  </div>
</template>

<script>
import HeaderSite from './components/HeaderSite.vue'
import MainSite from './components/MainSite.vue'

//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HeaderSite,
    MainSite
   
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

<template>
  <div id="app">
    <HeaderSite />
    <MainSite />
    <FooterSite />
    
  </div>
</template>

<script>
import HeaderSite from './components/HeaderSite.vue'
import MainSite from './components/MainSite.vue'
import FooterSite from './components/FooterSite.vue'

//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HeaderSite,
    MainSite,
    FooterSite
   
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

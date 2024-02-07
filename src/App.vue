<script>
  import headerDc from './components/headerDc.vue'
  import mainBody from './components/mainBody.vue'
  import blueIcons from './components/blueIcons.vue'
  import footerLists from './components/footerLists.vue'

  export default{
    components: {
      headerDc,
      mainBody,
      blueIcons,
      footerLists,
    }
  }
</script>




<template>
  
  <headerDc/>
  <mainBody/>
  <blueIcons/>
  <footerLists/>
  

  
</template>




<style lang="scss">
  @use "./assets/styles/general.scss" as *;
 
</style>

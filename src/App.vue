<script>
  import headerDc from './components/headerDc.vue'
  import mainBody from './components/mainBody.vue'
  import blueIcons from './components/blueIcons.vue'
  import footerLists from './components/footerLists.vue'
  import footerSignUp from './components/footerSignUp.vue'

  export default{
    components: {
      headerDc,
      mainBody,
      blueIcons,
      footerLists,
      footerSignUp,
    }
  }
</script>




<template>
  
  <headerDc/>
  <mainBody/>
  <blueIcons/>
  <footerLists/>
  <footerSignUp/>
  

  
</template>




<style lang="scss">
  @use "./assets/styles/general.scss" as *;
 
</style>

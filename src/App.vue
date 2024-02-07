<script>
  import headerDc from './components/headerDc.vue'
  import mainBody from './components/mainBody.vue'

  export default{
    components: {
      headerDc,
      mainBody,
    }
  }
</script>




<template>
  
  <headerDc/>
  <mainBody/>
  

  
</template>




<style lang="scss">
  @use "./assets/styles/general.scss" as *;
 
</style>

<template>
  <div>
    
    <navbar />
      <nuxt/>
    <footers/>
  </div>
</template>

<script>
  import Navbar from '~/components/Navbar.vue'
  import Footer from '~/components/Footer.vue'
  
   export default{
    components:{
      Navbar,
      "footers": Footer
    }
  }
</script>
<style>

</style>

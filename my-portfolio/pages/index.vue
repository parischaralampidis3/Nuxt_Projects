<template>
  <div id="app">
      <Hero />
      <Profile />  
      <Services />
     
  </div>
</template>
<script>
  import Hero from "~/components/Hero.vue"
  import Services from "~/components/Services.vue"
  import Profile from "~/components/Profile.vue"
 
  export default {
    components:{
      Hero,
      Profile, 
      Services
     
 
    }
  }
</script>
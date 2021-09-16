<template>
  <div id="app">
      <Hero />
      <Services />
      <Profile />
     
  </div>
</template>
<script>
  import Hero from "~/components/Hero.vue"
  import Services from "~/components/Services.vue"
  import Profile from "~/components/Profile.vue"
 
  export default {
    components:{
      Hero,
      Services,
      Profile
     
 
    }
  }
</script>
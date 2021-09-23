<template>
    <div class="container mx-auto">
                <AboutDetails />
                <AboutProfile />
    </div>
</template>


<script>
import AboutDetails from "~/partial/AboutDetails.vue"
import AboutProfile from "~/partial/AboutProfile.vue"
    export default{
        name:"about",
        components:{
            AboutDetails,
            AboutProfile
        }
    }
</script>
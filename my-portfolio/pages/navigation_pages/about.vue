<template>
    <div class="container mx-auto">
                <AboutDetails />
                <AboutProfile />
                <AboutEducation />
    </div>
</template>


<script>
import AboutDetails from "~/partial/AboutDetails.vue"
import AboutProfile from "~/partial/AboutProfile.vue"
import AboutEducation from "~/partial/AboutEducation.vue"   
    export default{
        name:"about",
        components:{
            AboutDetails,
            AboutProfile,
            AboutEducation
        }
    }
</script>
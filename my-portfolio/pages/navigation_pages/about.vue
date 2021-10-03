<template>
    <div class="container mx-auto">
                <AboutDetails />
                <AboutProfile />
                <AboutEducation />
                <AboutExperience />
    </div>
</template>


<script>
import AboutDetails from "~/partial/AboutDetails.vue"
import AboutProfile from "~/partial/AboutProfile.vue"
import AboutEducation from "~/partial/AboutEducation.vue"   
import AboutExperience from "~/partial/AboutExperience.vue"
    export default{
        name:"about",
        components:{
            AboutDetails,
            AboutProfile,
            AboutEducation,
            AboutExperience
        }
    }
</script>
<template>
    <div class="bg-white">
        <div class="container mx-auto">
            <div class="flex justify-between font-semibold px-4 py-4">
                <div>
                <nuxt-link to="/" class="brand text-2xl font-semibold">Home</nuxt-link>
                </div>
            <!--add nav --> 
                    <nav id="nav" class="hidden lg:block text-lg">
                        <nuxt-link to="../navigation_pages/portfolio">Portfolio</nuxt-link>  |
                        <nuxt-link to="../navigation_pages/about">About</nuxt-link>  |
                        <nuxt-link to="../navigation_pages/contact">Contact</nuxt-link>  
                    </nav> 
                <div class="md:block lg:hidden ">
                    <fa class="block text-2xl cursor-pointer" icon="bars" @click='handleClick'></fa>
                </div>
            <!--end of nav-->

            <div>
                <MobileMenu />
            </div>

            </div>
        </div>
    </div>
</div>
</template>
<script>
    import MobileMenu from "~/components/MobileMenu.vue"
    export default{
        name:"NavigationBar",
        data(){
            isOpen: false
        },
        methods: {
            handleClick(){
           this.isOpen = !this.isOpen
            }
                
            
        }
        
    }
</script>
<style>



</style>
<template>
    <div class="bg-white">
        <div class="section">
        <div class="container mx-auto">
            <div class="flex justify-between font-semibold text-gray-800 px-4 py-4">
                    <div>
                        <nuxt-link to="/" class="hidden lg:block brand text-2xl  hover:text-red-700  font-bold">Home</nuxt-link>
                    </div>
                    <nav id="nav" class="hidden lg:block  font-semibold text-xl">  
                    <nuxt-link to="../navigation_pages/about">About</nuxt-link>   |
                    <nuxt-link to="../navigation_pages/portfolio">Portfolio</nuxt-link>  |
                    <nuxt-link to="../navigation_pages/contact">Contact</nuxt-link>  
                    </nav> 
            </div>
        </div>
    </div>
    </div>
</div>
</template>
<script>
    import MobileMenu from "~/partial/MobileMenu.vue"
    export default{
        name:"NavigationBar",
        data(){
            return{
            isOpen: false
        }
        },
        methods: {
            handleClick(){
           this.isOpen = !this.isOpen
            }
        }
    }
</script>
<style scoped>
.section{
    padding-left:20px;
    padding-right:20px;
}
nav > li a:hover{
    color: tomato;
}
</style>
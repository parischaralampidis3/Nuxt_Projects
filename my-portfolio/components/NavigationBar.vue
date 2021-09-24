<template>
  
        <div class="section">
        <div class="container mx-auto">
            <div class="py-2">
            <div class="flex justify-between fixed top-0 z-10  bg-white left-0 right-0 opacity-100 font-semibold text-gray-800 px-12 py-3">
                    <div>
                        <nuxt-link to="/" class="hidden lg:block brand text-2xl   hover:text-red-700  font-bold">Home</nuxt-link>
                    </div>
                    <nav id="nav" class="hidden lg:block font-semibold text-xl">  
                    <nuxt-link to="../navigation_pages/about">About</nuxt-link>   |
                    <nuxt-link to="../navigation_pages/portfolio">Portfolio</nuxt-link>  |
                    <nuxt-link to="../navigation_pages/contact">Contact</nuxt-link>  
                    </nav> 
            </div>
        </div>
        </div>
    </div>


</template>
<script>

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
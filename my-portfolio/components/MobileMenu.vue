<template>
   <div>
   <client-only>
        <div class="bg-white">        
            <div class="container mx-auto"> 
                <nav>
                    <ul class="flex flex-col block font-semibold justify-center items-center  text-center text-gray-800 text-xl p-4  lg:hidden ">
                        
                        <nuxt-link to="/">Home</nuxt-link> 
                        <nuxt-link to="../navigation_pages/portfolio">Portfolio</nuxt-link>  
                        <nuxt-link to="../navigation_pages/about">About</nuxt-link>  
                        <nuxt-link to="../navigation_pages/contact">Contact</nuxt-link>  
                    </ul>
                </nav>
            </div>
        </div>
     </client-only>
    </div>
</template>
<style scoped>
ul li:hover{
    color:#bd1711;
}
</style>
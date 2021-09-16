<template>
   <div>
   <client-only>
        <div class="bg-gray-100">        
            <div class="container mx-auto"> 
                <nav>
                    <ul class=" block md:block font-semibold  text-center text-gray-800 text-xl p-4  lg:hidden ">
                        <li><a href="/">Home</a></li>
                        <li><a href="../navigation_pages/portfolio">Portfolio</a></li>
                        <li><a href="../navigation_pages/about">About</a></li>
                        <li><a href="../navigation_pages/contact">Contact</a></li>
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
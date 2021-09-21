<template>
    <div class="container mx-auto">

        <div class="mx-8">
          <h1 class="text-left font-bold  text-3xl">About</h1>
        </div>

        <div class="card flex flex-col justify-center items-center lg:flex-row  mt-4">
             
                    <div class="card-one">
                        <img class="rounded-full w-40 h-32 lg:mt-0 w-44 h-44" src="~/static/avatar.jpg">
                    </div>
                    
                        <div class="card two flex flex-col justify-around w-3/5 ">

                              
                                    <div class="text-center lg: mt-6">
                                            <div class="text-xl md:text-2xl font-semibold lg:text-4xl ">
                                                <h3 >Hello my name is Paris</h3>
                                            </div>
                                                <div class ="uppercase mt-2 text-base  md:text-2xl mx-auto w-3/3">
                                                    <p>front end developer based in greece</p> 
                                                </div>
                                                    <div class=" mt-6 text-left leading-6 mx-auto  md:mx-auto w-2/3">
                                                        <p >Lorem ipsum dolor sit amet,
                                                        consectetur adipiscing elit. Nulla vehicula nisi vitae 
                                                        accumsan aliquet. Vivamus hendrerit nibh sapien, convallis 
                                                        cursus mauris facilisis congue. Ut ac ante et est posuer
                                                        e tempus.</p> 
                                                    </div>
                                        
                                        <div class="button text-white text-center w-28 font-bold bg-gray-600 rounded-xl p-2 mt-8 mx-auto">
                                            <button><a href="./navigation_pages/about" target="_blank">Learn More</a></button>
                                        </div>
                                    </div>        
                        </div>
            </div>
    </div>      
</template>
<style scoped>
.section{
    padding-left:20px;
    padding-right:20px;
}
.button{

box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.14);
-webkit-box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.14);
-moz-box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.14);
}

</style>
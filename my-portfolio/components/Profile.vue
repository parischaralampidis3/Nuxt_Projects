<template>
    <div class="container mx-auto">

        <div class="mx-8 text-left font-bold mt-8 text-3xl">
          <h1>Biography</h1>
        </div>

        <div class="profile-card flex flex-col justify-center items-center lg:flex-row  mt-4">
             
                    <div class="profile-card-one">
                        <img class="rounded-full w-40 h-32 lg:mt-0 w-44 h-44" src="~/static/avatar.jpg">
                    </div>
                    
                        <div class="profile-card-two flex flex-col justify-around w-3/5 ">

                              
                                    <div class="text-center lg: mt-6">
                                            <div class="font-bold text-xl md:text-2xl  lg:text-4xl ">
                                                <h3 >Hello, my name is Paris</h3>
                                            </div>
                                                <div class ="uppercase font-semibold mt-2 text-base  md:text-2xl mx-auto w-3/3">
                                                    <p>front end developer based in greece</p> 
                                                </div>
                                                    <div class=" mt-6 text-left leading-6 mx-auto  md:mx-auto w-3/4">
                                                        <p >Lorem ipsum dolor sit amet,
                                                        consectetur adipiscing elit. Nulla vehicula nisi vitae 
                                                        accumsan aliquet.</p> 
                                                    </div>
                                        
                                        <div class="profile-button text-center text-white  bg-red-600 rounded-xl p-2 mt-8 mx-auto lg:w-1/3">
                                            <button ><a class=" uppercase text-sm font-semibold" href="./navigation_pages/about" target="_blank">Learn More</a></button>
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
.profile-button{
    box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.14);
    -webkit-box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.14);
    -moz-box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.14);
}

</style>
<template>
    
        <div class="container mx-auto">
            <div class="hero-image">
                <div class="hero-text text-white text-center ">
                    <h1 class="font-bold text-2xl">Paris Charalampidis</h1>
                    <p class="italic">I am a Front End Developer.</p>
                    <div class="mt-6 ml-15">
                    <a class="button font-semibold bg-gray-600 rounded-2xl p-2  hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50"  href="resume.pdf" download>Download</a>
                    </div>
                </div>
            </div>    
        </div>
    
</template>
<style scoped>
   
.hero-text{
  position: absolute;
  top:50%;
  left:50%;
  transform: translate(-50%, -50%);
}

.hero-image{
    background-image:linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.2)),
    url("~/static/cover-photo.jpg");
    height:300px;
    background-position:center;
    background-repeat:no-repeat;
    background-size:cover;
    position:relative;
}
.button{

box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.34);
-webkit-box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.34);
-moz-box-shadow: 2px 3px 4px 1px rgba(0,0,0,0.34);
}


</style>
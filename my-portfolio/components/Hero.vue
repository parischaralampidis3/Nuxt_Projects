<template>
    
        <div class="container mx-auto">
            <div class="modal">
                <Modal v-show="showModal"  />
                
            </div>

            <div class="hero-image ">
                <div class="hero-text text-white text-center ">
                    <h1 class="font-bold text-2xl">Paris Charalampidis</h1>
                        <div class=" flex text-sm mt-6 mx-6 " >
                                 <fa class="mr-2" icon="phone"></fa>
                                 <p>(+30)6947491008</p>
                        </div>
                        <div class=" flex text-sm mt-6 mx-6 " >
                                 <fa class="mr-2" icon="envelope"></fa>
                                 <p>parou.char@gmail.com</p>
                        </div>
                    <div class="mt-6 ml-15">
                    <a id="hero-modal" class="button font-semibold bg-gray-600 rounded-2xl p-2  hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50"  @click="setNotification" >Download Resume</a>
                    </div>
                  
                </div>
            
            
            </div>    
        </div>
    
</template>
<script>
 import Modal from "~/partial/Modal.vue"
    export default{
        name: "Hero",
        components:{
         Modal
        },
        data(){  
            return{
                showModal: false,
            }
        },
        methods:{
            setNotification(){
                setTimeout(() =>{
                    this.showModal = true;
                },1000);
            }
        },
    }
</script>
<style scoped>
#hero-modal{
    visibility: block;
}
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
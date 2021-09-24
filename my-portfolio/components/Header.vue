<template>
   
    
        <div class="container mx-auto">
            
                <div class="flex justify-between inset-x-0 fixed   z-10  mt-4 ml-0 mr-0 py-2 px-12 bg-white " >
                    <div class=" sm:hover:text-red-700 lg:hidden"> 
                        <a href="/"> <fa class=" text-2xl cursor-pointer " icon="home"></fa></a>
                    </div>
                    <div class=" lg:hidden block">             
                        <fa class=" text-2xl cursor-pointer " icon="bars" @click='handleClick'></fa>
                    </div>
                </div>
                <div class="  font-semibold">            
                    <NavigationBar/> 
               </div>
                <div v-show="isOpen">
                    <MobileMenu />
                </div>
            </div>
      
</template>
<script>
    import NavigationBar from "~/components/NavigationBar.vue"
    import MobileMenu from "~/partial/MobileMenu.vue"
    export default{
        name:"Header",
        components:{
            NavigationBar,
            MobileMenu
        },
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

</style>
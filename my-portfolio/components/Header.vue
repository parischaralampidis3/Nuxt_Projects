<template>
    <div class="bg-white">
    
        <div class="container mx-auto">
                <div class="flex justify-between mt-4 mx-4" >
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
        </div>
    
    </div>
</template>
<script>
    import NavigationBar from "~/components/NavigationBar.vue"
    import MobileMenu from "~/components/MobileMenu.vue"
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
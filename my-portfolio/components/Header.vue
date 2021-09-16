<template>
    <div class="bg-white">
        <div class="container mx-auto">
            <div class="flex justify-end mt-4 mr-8 lg:hidden block">             
               <fa class=" text-2xl cursor-pointer " icon="bars" @click='handleClick'></fa>
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
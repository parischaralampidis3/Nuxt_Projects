<template>
    <div class="container mx-auto">
         <div class="modal-overlay">
             <div class="modal bg-red-500">     
                    <div>
                         <h1 class="text-base font-semibold text-white">Thank you for downloading my resume!</h1>
                         <a href="/">x</a>
                    </div>    
            </div>
        </div>
    </div>
</template> 
<script>
    export default{
        
    }
</script>
<style scoped>
.modal-overlay {
margin-bottom:25px;
  display: flex;
  justify-content: center;
  padding:10px;
  
}
.modal-overlay:target{
  visibility: hidden;
}

.modal {
  position:relative;
  text-align: center; 
  height: 100px;
  width: 400px;
  border-radius:8px;
  margin-top:30px;
  padding:1em;
}
a{ 
  color:white;
  position:absolute;
  top:15px;
  right:10px;
}

</style>
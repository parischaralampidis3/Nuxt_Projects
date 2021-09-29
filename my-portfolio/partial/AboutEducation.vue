<template>
  <div class="container mx-auto">

    <div class=" flex flex-col justify-center items-center p-4 mt-4">

        <div class="text-center text-base font-bold bg-gray-700 text-white w-64  p-4 w-3/5 h-3/4">
            <h1>Education</h1>
        </div>    

       <div class=" flex justify-around text-center font-semibold text-2xl p-2 w-2/5">
             <fa class="text-4xl mx-2 text-red-700 " icon="university"></fa>
            <h1>Education</h1>
       </div>
       <div class="aboutTable text-left mt-8 border">
         <table style="width:100%">
           <tr>
             <th>University</th>
             <th>Date</th>
             <th>Field</th>
           </tr>
         
           <tr>
             <td>Akto art and Design College</td>
             <td>2007-2009</td>
             <td>Sketch-Comics-cartoon</td>
           </tr>  
           <tr>
             <td>Aristotle University of Thessaloniki</td>
             <td>2002-2016</td>
             <td>Theology</td>
           </tr>
             <tr>
             <td>Social Hackers Academy</td>
             <td>2018-2019</td>
             <td>Full Stack Development</td>
           </tr>
        </table>
      </div> 

       <div class=" flex justify-around text-center font-semibold text-2xl mt-4 p-2 w-2/5">
             <fa class="text-4xl text-red-700 mx-2 " icon="briefcase"></fa>
            <h1>Experience</h1>
       </div>
       <div class="aboutTable text-left mt-8 border">
         <table style="width:100%">
           <tr>
             <th>Work/Type</th>
             <th>Date</th>
             <th>Speciality</th>
           </tr>
         
           <tr>
             <td>Akto art and Design College</td>
             <td>2007-2009</td>
             <td>Sketch-Comics-cartoon</td>
           </tr>  
           <tr>
             <td>Aristotle University of Thessaloniki</td>
             <td>2002-2016</td>
             <td>Theology</td>
           </tr>
             <tr>
             <td>Social Hackers Academy</td>
             <td>2018-2019</td>
             <td>Full Stack Development</td>
           </tr>
        </table>
      </div> 

    </div>   
  </div>
</template>
<style scoped>
table, th, td{
  padding:10px;
  background:#ddd;
  border:0.02px solid gray;
}
td{
  background:white;
}
th{
  color:#454545;
}
td:first-child{
  color:red;
  font-weight:600;
  font-size:17px;
}
</style>
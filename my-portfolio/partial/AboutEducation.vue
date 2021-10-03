<template>
  <div class="container mx-auto">

    <div class=" flex flex-col justify-center items-center  p-4 mb-8 mt-4">

        <div class="text-center text-base font-bold bg-gray-700 text-white w-64  mb-8 p-4 w-4/5 h-3/4">
            <h1>Education</h1>
        </div>    

       <div class=" flex justify-around text-center font-semibold text-2xl mb-8 p-2 w-2/5">
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
       <div class="aboutTable text-left mt-8">
         <table class="w-full mb-8">
           <tr>
             <th>Work/Type</th>
             <th>Date</th>
             <th>Speciality</th>
           </tr>
            <tr>
              <td>Istogram</td>
              <td>2021 - Present</td>
              <td>Front end Developer</td>
            </tr>
           <tr>
             <td>Teleperformance Hellas </td>
             <td>2019-2021</td>
             <td>Customer care agent</td>
           </tr>  
           <tr>
             <td>Self employed</td>
             <td>2012-2018</td>
             <td>Freelancer Illustrator/Animator</td>
           </tr>
             <tr>
             <td>MRB Hellas</td>
             <td>2007-2009</td>
             <td>Phone call center agent</td>
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
  
  font-weight:600;
  font-size:17px;
}
</style>
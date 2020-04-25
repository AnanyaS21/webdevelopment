<style>
  .hover-ex{
  width: 100px;
  height: 100px;
  background-color:limegreen;
  color: white;
  }
  .hover-ex:hover{
  background-color: crimson;
  width: 150px;
  height:150px;
  }
  </style>
  <div class="hover-ex"> Move your mouse here</div>
  <style>
  .first-child-ex{
  color:crimson;
  }
  .first-child-ex:first-child{
  color:blue;
  }
  </style>
  <ol>
  <li class="first-child-ex"> First </li>
   <li class="first-child-ex"> Second </li>
   <li class="first-child-ex">Third</li>
  </ol>
  
   <style>
  .box-1{
  border: 1px solid black;
  color:white;
  background-color:blue;
  height: 150px;
  width:300px;
  }
  .box-2{
  border: 1px solid black;
  color:white;
  background-color: red;
  height: 100px;
  width:300px;
  }
  .box-3{
  border: 1px solid black;
  color:white;
  background-color:green;
  height: 200px;
  width:100px;
  }
   .flex-container{
    display:flex;
    width:100px;
    border: 5px dotted pink;
    flex-wrap: wrap;
  }
 
  .column{
    flex-direction: column-reverse;
  }
  
  </style>
  <div class="flex-container column">
    <div class="box-1"> 1</div>
    <div class="box-2"> 2</div>
    <div class="box-3"> 3</div>
  


   
  
  

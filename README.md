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
  
  .ex-box{
  border: 3px solid blue;
  background-color: #eee;
  height:200px;
  width:200px;
  display:flex;
  align-items: center;
  justify-content: center;
  float: left;
  margin-right: 10px;
  border-radious: 5px;
  font-size: 30px;
  }
  .ex-box:last-of-type{
  clear: right;
  }
  </style>
  <div class="ex-box"> BOX 1</div>
  <div class="ex-box"> BOX 2</div>
  
  <style>
   .example{
  border: 3px solid pink;
  padding:5px;
  margin: 25px;
  background-color: white;
  }
  </style>
  <div class="example"> Content written inside box </div>

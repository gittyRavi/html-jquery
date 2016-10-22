<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js">
</script>
<script>
$(document).ready(function(){
 $("#t").click(function(){
  $("#y").animate({
       left : '1270px',
       height :'60px' ,
       width :'60px' ,
       opacity :'0.5',
      },2000);
  $("#z").fadeToggle(2000).$(this).show();              /* codes not for use in IE */
  });
 });
$(document).ready(function(){
  $("#flip").click(function(){
   $("#panel").slideToggle("slow");
  });
 });
$(document).ready(function(){
 $("#k").click(function(){$("#q").fadeToggle(2000);});
 });
</script>
<style type="text/css">
h3{background-color : pink;}
#y
    {
      padding : 5px;
      text-align : center;
     }
#panel,#flip
    {
      padding : 5px;
      text-align : center;
      text-size : 20px;
      background-color : green;
      border : solid 2px black;
      border-radius : 5px;
      -webkit-border-radius : 5px;
    
      }
#panel
      {
       padding : 50px;
       display : none;
      }
body{background-color:black;}
button{
       background-color:lightblue;
       transform:rotate(45deg);
	     height:40px;
	     width:40px;
	     border-radius:10px;
      }
</style>
</head>
<body>
<div id="flip">
Click me
</div>
<div id="panel">
Hi howdy!!!
</div>
<p>
<div style="height:40px;width:40px;background-color:red;border-radius:25px;color:green;position:relative" id="y">
<pre>Woohoo</pre>
</div>
</p>
<hr width="100%" height="4px" color="blue" align="center" />
<h3>
<center>
<b style="color:blue;transform:rotate(-45deg)"  id="k">
for&nbsp &nbsp 
<button id="t" align="center">
<p style="transform:rotate(-45deg);color:red">
<b id="q">
click
</b>
</p>
</button>
&nbsp animation
</b>
<br>
</h3>
<hr width="100%" height="4px" color="lightblue" align="center" />
<img src="C:\Users\ravi\Documents\notepad++\swamp-nature.jpg" alt="Swamp" style="display:none;width:1325px" id="z">
</img>
</center>
</body>
</html>

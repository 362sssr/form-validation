# form-validation
:  
 FORM 
 HTML 
<html> 
<head> 
<title>css styles</title> 
<link rel="stylesheet" href="tikki.css"> 
</head> 
<body><fieldset id="miraculous">TIKKI PROGRAMMING CENTER</fieldset> <p>hello guys!!!!!!! <br> 
welcome to my programming center</p> 
i'm here to guide and support u for all ur programming work. And i havealso included some fun sectors for u, while programming. </p> 
<h1>Lets have lot more fun and thrill in our programs</h1> <br><br> 
<br> 
<br>
<fieldset id="miraculous"> 
<legend>PROGRAMMING SPACE</legend> 
<textarea name="ab" rows="10" columns=""></textarea> </fieldset> 
enter any number between 0-9:<input type="number" id="numb"><BR> enter your birth month:<input type="text" id="month"> <p align="center"><BR><button onclick="lb()" >lucky charm</button> </p> 
<p id="demo"></p> 
<script src="tikki.js"> 
</script> 
 JAVA 
function lb() { 
let x = document.getElementById("numb").value; 
let y= document.getElementById("month").value; 
let text; 
 if ( x < 1 || x > 10||y=="") { 
 text = "Input not valid"; 
 } 
else{ 
if (y=="june"){ 
 text = "you are THE ANGEL OF JUSTICE"; 
 } 
else{ 
text="try again"} 
} document.getElementById("demo").innerHTML = text; } 
 CSS 
#miraculous 
{text-align:center;background-color:red;} 
body{background-color:black;color:white;} button{padding:10px;spacing} 

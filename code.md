MAIN PROGRAM:


<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.button {
    background-color:purple;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.container {
    position: relative;
    text-align: center;
    color: white;
}
.centered {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.mySlides {display:none;}
</style>
</head>
<body>

<div class="container" style="max-width:1000px">
  <img class="mySlides" src="s1.jpg" style="width:200%">
  <img class="mySlides" src="s6.jpg" style="width:200%">
  <img class="mySlides" src="s4.jpg" style="width:200%">
  <img class="mySlides" src="s2.jpg" style="width:200%">  
<div class="centered"><h1><font size="13">AKSHAYA SCHOOL OF LEARNING.......</font></h1><form action="login.html">
<input type="submit" class="button" value="CLICK HERE"><br>to view full page
</form></div>
</div>
<script>
var myIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 2000); // Change image every 2 seconds
}
</script>
</body>
</html>



Sub Program 1 for Login webpage:




<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.centered {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>
</head>
<body>
<div class="container">
  <img src="l1.jpg" alt="Snow" style="width:300%;">
  <div class="centered"><form action="aca.html"><br><br><br><br>
<input type="submit" class="button" value=" ACADEMICS">
</form><br><form action="fac.html">
<input type="submit" class="button" value="   FACILITIES">
</form><br><form action="events.html">
<input type="submit" class="button" value="     EVENTS  ">
</form><br><form action="campuslife.html">
<input type="submit" class="button" value="CAMPUS LIFE">
</form><br><form action="contact.html">
<input type="submit" class="button" value="CONTACT US">
</form></div></div>
  </div>
</body>
</html>



Sub Program 2 for Academics webpage:



<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.button {
    background-color:purple;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.button1 {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 10px 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 10px;
    margin: 4px 2px;
    cursor: pointer;
}
.container {
    position: relative;
    text-align: center;
    color: white;
}
.centered {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.mySlides {display:none;}
</style>
</head>
<body>
<div class="container" style="max-width:1000px">
  <img class="mySlides" src="a1.jpg" style="width:150%">
  <img class="mySlides" src="a2.jpg" style="width:150%">
  <img class="mySlides" src="a3.jpg" style="width:150%">
    <form action="login.html">
<input type="submit" class="button1" value="back">
</form>
<div class="centered"><h1><font size="9">"To impart quality higher education and to undertake research and extension with emphasis on
application and innovation that cater to the emerging societal needs through all-round
development of students of all sections enabling them to be globally competitive and socially
responsible citizens with intrinsic values"</font><br></div>
</div>
<script>
var myIndex = 0;
carousel();
function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 2000); // Change image every 2 seconds
}
</script>
</body>
</html>

Sub Program 3 for Campus Life webpage:


<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.button {
    background-color:purple;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.button1 {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 10px 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 10px;
    margin: 4px 2px;
    cursor: pointer;
}
.container {
    position: relative;
    text-align: center;
    color: white;
}
.centered {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.mySlides {display:none;}
</style>
</head>
<body>
<div class="container" style="max-width:1000px">
  <img class="mySlides" src="c2.jpg" style="width:150%">
  <img class="mySlides" src="c4.jpg" style="width:150%">
  <img class="mySlides" src="c1.jpg" style="width:150%">
  <img class="mySlides" src="c5.jpg" style="width:150%">
     <form action="login.html">
<input type="submit" class="button1" value="back">
</form>
<div class="centered"><h1><font size="9">"STUDENTS ENJOY LEARNING IN SCHOOL.THEY FEEL THE JOY OF LEARNING"</font><br></div>
</div>
<script>
var myIndex = 0;
carousel();
function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 2000); // Change image every 2 seconds
}
</script>
</body>
</html>

Sub Program 4 for Event webpage:



<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.button {
    background-color:purple;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.button1 {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 10px 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 10px;
    margin: 4px 2px;
    cursor: pointer;
}
.container {
    position: relative;
    text-align: center;
    color: white;
}
.centered {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.mySlides {display:none;}
</style>
</head>
<body>

<div class="container" style="max-width:1000px">
  <img class="mySlides" src="e7.jpg" style="width:150%">
  <img class="mySlides" src="e8.jpg" style="width:150%">
  <img class="mySlides" src="e11.jpg" style="width:150%">
    <form action="login.html">
<input type="submit" class="button1" value="back">
</form>
<div class="centered"><h1><font size="9">"In an exhibition, students get a chance to apply or do the practical aspect of the things that they have learned from the Science exhibitionclassroom. These are real opportunities for the kids to easily implement the things that they have learn from schools."</font><br></div>
</div>
<script>
var myIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 2000); // Change image every 2 seconds
}
</script>
</body>
</html>


Sub Program 5 for Facilities webpage:



<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.button {
    background-color:purple;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.container {
    position: relative;
    text-align: center;
    color: white;
}
.button1 {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 10px 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 10px;
    margin: 4px 2px;
    cursor: pointer;
}
.centered {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.mySlides {display:none;}
</style>
</head>
<body>

<div class="container" style="max-width:1000px">
  <img class="mySlides" src="f1.jpg" style="width:200%">
  <img class="mySlides" src="f2.jpg" style="width:200%">
  <img class="mySlides" src="f3.jpg" style="width:200%">    
<form action="login.html">
<input type="submit" class="button1" value="back">
</form>
<div class="centered"><h1><font size="9"><br>"Good schools combine classroom teaching with laboratory experiments to ensure that their students grasp each and every concept thoroughly. It is also believed that laboratory teaching and experiments that are being conducted here help encourage deep understanding in children."</font><br></div>
</div>
<script>
var myIndex = 0;
carousel();
function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 2000); // Change image every 2 seconds
}
</script>
</body>
</html>



Sub Program 6 for Contact webpage:



<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.centered {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.button1 {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 10px 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 10px;
    margin: 4px 2px;
    cursor: pointer;
}
</style>
</head>
<body>
<div class="container">
  <img src="b4.jpg" alt="Snow" style="width:150%;">
  <div class="centered"><h1><font size="9"><br>contact us:<br>akshay@aks.in<br><br>ping us:<br>akshay.fb.in<br><br>call us at:<br>988748374873<br><br></font><br></div></div></div>
<form action="login.html">
<input type="submit" class="button1" value="back">
</form> 
 </div>
</body>
</html>

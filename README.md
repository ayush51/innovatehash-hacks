# innovatehash-hacks
# We plan to create a website through which immediate help to patients can be provided. We ll try to create something that would provide the data of the hospital whose ambulance would reach to the patient in the shortest time possible.

<!DOCTYPE html>
<html>
<head>
<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: red;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    text-decoration: none;
}

li a:hover {
    background-color: red;
}
.boxed1 {
  border: 1px ;
  height: 400px;
  width: 300px;
  background-color: #0099ff;
  align-self: right;
}
.button {
  font: bold 18px Arial;
  text-decoration: none;
  background-color: #ff3399;
  color: white;
}
</style>
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body>

<ul>
  <li style="width: 1300px"><a class="active" href="#home"><marquee direction="right" scrollamount="15"><P style="font-color: white; font-size: 50px;">HELPING DESK<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1oUG9qdepQl0A0rsn2TLN01SQ0VsQlOJI2tIUb7r4cbXhXd8w" hspace="20" style="height: 35px; width:50px;white-space: pre;"></P></marquee></img></a></li></ul>

  <div style="float: left; background-size: contain;height: 450px;width: 950px;margin-left: 40px; background-image:url('final.jpg'); opacity: 0.5"> <span style="color: black;font-size: 40px;"><i>We provide 24 X 7 emergency support. You can get an ambulance at your door in the shortest time possible from the best hospitals in your town. </i></span>
    

  </div>
 

   <div align="right" style="margin:40px">

<div class="boxed1">
<div style="margin:20px">
<h2 style="font-family: arial-black;color:white;font-weight: 700; text-align: center;"> Provide your details </h2><hr>
<form name="myform" onsubmit="return CheckPwd()" style="text-align: left;margin: 20px;font-size: 15px;font-family: arial ;" method="post">
<p style="margin-top: 40px;">
 <input type="text" name="fn" placeholder="First Name" style=" font-size: 15px;text-align: left;width: 100%;height: 40px;" required><br><br>
  <input type="text" name="tn" placeholder="Last Name" style=" font-size: 15px;text-align: left;width: 100%;height: 40px;" required><br><br>

 <input type="email" name="ID" placeholder="Email Id" style=" font-size: 15px;text-align: left;width: 100%;height: 40px;" required><br><br>
  
<input type="number" name="ID" placeholder=" Contact Number" style=" font-size: 15px;text-align: left;width: 100%;height: 40px;" required><br> <br>

  <a href="" class="button">Look for an Ambulance</a> </form>
  
   </div>
   </div>
</body>
</html>
  

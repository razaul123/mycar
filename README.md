# mycar
<!DOCTYPE html>
<html>
  <head>
    <title>My Car</title>
    <style>
    body {
        background-color: light blue;
      }
      body{
        text-align: center;
        color: green;
      }
      </style>
     <script src="carjs.js"></script> 
  </head>
  <body>
    <h1>You Car</h1>
    <h3>Get your car that you want</h3>
    <button type="button" id="button" onclick="document.getElementById('car').innerHTML = getCar();">Click Now</button>
    <p id="car"></p>
  </body>
</html>

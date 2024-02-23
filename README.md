<!DOCTYPE html>
<html>
<body>
<canvas id="myCanvas" width="500" height="500" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML5 canvas tag.</canvas>

<script>
// Get the canvas and context
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");

// Draw the black triangle
ctx.beginPath();
ctx.moveTo(100, 100);
ctx.lineTo(250, 100);
ctx.lineTo(175, 250);
ctx.fillStyle = "black";
ctx.fill();
ctx.closePath();

// Draw the red triangle
ctx.beginPath();
ctx.moveTo(175, 250);
ctx.lineTo(250, 100);
ctx.lineTo(325, 250);
ctx.fillStyle = "red";
ctx.fill();
ctx.closePath();
</script>

</body>
</html>

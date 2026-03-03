<!DOCTYPE html>
 <html>
<head>
<title>Simple DOM Style Change</title>
</head>
<body>
<h2 id="text">Hello Students</h2>
<button onclick="changeStyle()">Change Style</button>
<script>
 {
function changeStyle()
document.getElementById("text").style.color = "red";
document.getElementById("text").style.fontSize = "25px";
}
</script>
 </body>
</html>

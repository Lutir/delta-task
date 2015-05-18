HTML CODE-

<!doctype html>
<html>

<head>
<title>Swap Colors</title>
<link rel="stylesheet" type="text/css" href="color.css">
<script src="color.js"></script>
</head>

<body>

<div id="color1"   onclick="changeColor();"></div>
<script type="text/javascript">
var z = document.getElementById("color1");
   z.style.backgroundColor = 'rgb(' + (Math.floor(Math.random() * 256)) + ',' + (Math.floor(Math.random() * 256)) + ',' + (Math.floor(Math.random() * 256)) + ')';
</script>
<div id="color2"   onclick="changeColor2();"></div>
<script type="text/javascript">
var a = document.getElementById("color2");
   a.style.backgroundColor = 'rgb(' + (Math.floor(Math.random() * 256)) + ',' + (Math.floor(Math.random() * 256)) + ',' + (Math.floor(Math.random() * 256)) + ')';
</script>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>js</title>
<script>
function myFunction(){
	document.getElementById("demo").innerHTML="Hello World";
}
</script>
</head>
<body>

<p>单击按钮触发函数。</p>
<button onclick="myFunction()">点我</button>
<p id="demo"></p>

</body>
</html>

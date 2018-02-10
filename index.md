<!DOCTYPE html>
<html>
<head>
<meta charset ="utf-8"/>
<title>Shopping list</title>
<style>
body{color:white;
 background-image:url(9.png);
background-color:black;
 background-size:100% 100%;
 height:100%;
 }
 html{
 height:100%;
 }
 @keyframes myfirst{
 	from{opacity: 0}
 	to{opacity: 100}
 }
 h1,p,ul{
 	animation: myfirst 1s infinite;
 }
</style>
</head>
<body>
<audio src="1.mp3" controls="controls" autoplay="autoplay">
</audio>
<h1>乃事to米球</h1>
<p title="a gentle reminder">
你好啊</p>
<ul id="purchases">
<li class="sale">儿子</li>
<li class="sale important">儿子</li>
<li> 我是你爸爸</li>
</ul>
<script>
var items=document.getElementByTagName("li");
for(var i=0;i<items.length;i++){	
alert(typeof items[i]);
}
</script>
</body>
</html>


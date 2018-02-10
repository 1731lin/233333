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
 	animation: myfirst 3s infinite;
 }
</style>
</head>
<body>
<h1>What to buy</h1>
<p title="a gentle reminder">
Don't forget to buy this stuff.</p>
<ul id="purchases">
<li class="sale">Cheese</li>
<li class="sale important">Milk</li>
<li> 林盛斌最帅</li>
</ul>
<script>
var items=document.getElementByTagName("li");
for(var i=0;i<items.length;i++){	
alert(typeof items[i]);
}
</script>
</body>
</html>

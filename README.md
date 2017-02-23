<!DOCTYPE html>
<html>
<title>colorcircle</title>
<head>
<style>
h2{
    font-family: sans-serif;
    text-align: center;
    padding: 36px;
}
.Tab{
    height: 400px;
    background: gainsboro;
}
#circle{
	width: 15%;
    height: 150px;
    background: white;
    float: left;
    margin-left: 220px;
    margin-top: 95px;
    border-radius: 155px;
    text-align: center;
}
#one{
    width: 15%;
    height: 70px;
    background: black;
    float: right;
    margin-right: 515px;
    margin-top: 38px;
	color:white;
}
#two{
	width: 15%;
    height: 70px;
    background: red;
    float: right;
    margin-right: 515px;
    margin-top: 20px;
}
#three{
    width: 15%;
    height: 70px;
    background: blue;
    float: right;
    margin-right: 515px;
    margin-top: 20px;
}
</style>
</head> 
<body>
<div class="Tab">
	<div id="circle">
		<h2>circle</h2>
	</div>
	<button id="one"onclick="changeBlack()">Black</button>
	<button id="two"onclick="changeRed()">Red</button>
	<button id="three"onclick="changeBlue()">Blue</button>
</div>
<script>
function changeBlack(){
	document.getElementById('circle').style='background:black';
}
function changeRed(){
	document.getElementById('circle').style='background:red';
}
function changeBlue(){
	document.getElementById('circle').style='background:blue';
}
</script>
</body>
</html>

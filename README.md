<html>
<head>
<title>Animation</title>
<style>
.box{
width:100px;
height:100px;
background-color:orange;
animation:colorChange 4s;
}
@keyframes colorChange{
0%{
background-color:red;
}
25%{
background-color:yellow;
}
50%{
background-color:green;
}
75%{
background-color:blue;
}
}
</style>
</head>
<body>
<div class="box"></div>
</body>
</html>

<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">

  <title>浏览器的信息输入和输出，实现猜数游戏1</title>
  <script type="text/javascript">
  <!--
    //Math对象有一些常用方法，用于解决数学问题
	var num1 = Math.floor(Math.random()*10) ;
	//console.log是JavaScript对后台的标准输出方式，后台也称Console，桌面的浏览器一般都有专门的界面实现Console功能，也用作开发者对代码的调试。
        console.log("偷偷告诉你，是 "+num1);
	var guess = prompt("从0到9，你赌几？");
	    guess = parseInt(guess);
	if (num1===guess){
		alert("你赢了 !");
	}else{
	    alert("你输了 ! \nIt's "+num1);
	}
  //-->
  </script>
 </head>
 <body>
  
 </body>
</html>

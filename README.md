qrcode_swq666666.github.io.png
<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

<!--   标签（搜索引擎） -->
  <title>  
  happy every day
  </title>

<!-- //外观（style） -->
  <style>  
  
  body{
      background-color:#fdd; '背景颜色纯色
	  margin:0;              'body元素的margin属性设为0，可以把页面设为全屏设定
	  font-size:20px;
  }

  h1{
    margin:0;
	padding:2%;
    font-size:40px;
    color:pink;
	text-align:center;	'文字居中
    height:10px;
	background:url(../picture/背景图1.jpg);
  }

'难点：给列表定位，利用position(absolute,relative)
/*ol相当于列表list的父亲，类似于body*/
  
/*对列表的内容进行外观修饰*/
  ol{}

  ol li{
	 font-size:1.5em;
	 color:pink;
     font-family:汉仪彩云体简;
	 margin:10px;
	 list-style-type:none;
	 padding:10px;
  }

  #right{
       float:right;
       text-align:center;
	   height:100%;
	   width:48%;
	   margin:2%;
	   padding:2%;
	   font-size:40px;
	   font-weight:bold;
	   color:#ffb;
	   border:2px solid #aaa;
       background:url(../picture/背景图2.jpg);
  }


  </style>  

 </head>

 <body>

<!-- 大标题 -->

 <h1>
  Hello!
<!--   在网页上使用图像之前，应该通过软件把图像处理为合适的尺寸 -->
 </h1> 

<!--  创建无序列表ul li和有序列表 ol li-->

 <ol>
	<li>
<!--  在列表里面添加超链接，使得可以跳转到目的页面 -->
	  <a href="https://github.com/Yunzhy/yunzhy.github.io">我的仓库</a>
	</li>
	<li>
	  <a href="https://github.com/Yunzhy/yunzhy.github.io/tree/main/Test_3">作业共享</a>
	</li>
    <li>
	  <a href="https://github.com/Yunzhy/yunzhy.github.io/tree/main/%E4%BD%9C%E4%B8%9A1">小小测试</a>
	</li>
	<li>
	  <a href="">点击Tow</a>
	</li>
	<li>
      <a href="">点击Three</a>
	</li>
 </ol>

<!--  在body里面设置盒状模型，左右 -->

 <div id="right" class="">
	欢迎来到Yun的网站~
 </div>

 <div id="h1" class="">
	
 </div>
  <p>
  </p>

 </body>
</html>

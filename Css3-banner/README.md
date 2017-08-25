最新研究成果，CSS实现轮播~

.banner .main{width:500%;height:450px;position:absolute;top:0;-webkit-animation:slide 15s infinite;/*动画名称 时间  循环*/}

@-webkit-keyframes slide{

		0%{left:0;}
		
    20%{left:0;}
		
    21%{left:-100%;}
		
    40%{left:-100%;}
		
    41%{left:-200%;}
		
    60%{left:-200%;}
		
    61%{left:-300%;}
		
    80%{left:-300%;}
		
    81%{left:-400%;}
		
    100%{left:-400%;}
	}
  @-webkit-keyframes slide_2{
  
		0%{background:red;left:0;}
		
    20%{background:red;left:0;}
		
    21%{background:#330099;left:20px;}
		
    40%{background:#330099;left:20px;}
		
    41%{background:#cc0000;left:40px;}
		
    60%{background:#cc0000;left:40px;}
		
    61%{background:#330033;left:60px;}
		
    80%{background:#330033;left:60px;}
		
    81%{background:#ffff00;left:80px;}
		
    100%{background:#ffff00;left:80px;}
	
  }

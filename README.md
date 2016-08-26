# peg-efull-screen
网页全屏<br>
用css实现空标签占满全屏<br>
关键代码
```css
html,body{
	height: 100%;
//	overflow: hidden;   //隐藏浏览器默认滚动条
}
#container,.sections,.section{
	height: 100%;
}
```
背景图片居中自适应显示
```css
#section1,
#section2,
#section3,
#section4{
	background-size: cover;
	background-position:50% 50% ;
	text-align: center;
}
```

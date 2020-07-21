js数组遍历{
	1.for循环
	for(j=0,len=arr.length;j<len;j++){}
	
	2.forEach()循环
	
	3.map循环:map()中传入
	
	4.for..in循环可用于循环对象和数组
	
	let obj = {
		name: '王大锤',
		age:'18',
		weight:'70kg'
	}
	for(var key in obj){
		console.log(key);//name age weight 返回的是数组索引
		console.log(obj[key]);//王大锤 18 70kg
	}
      for...of 用于循环对象属性
	
}


清除浮动
css浮动:浮动的元素会脱离正常的文档,在正常的文档流中不占用空间
			float属性:
				left
				right
			流式布局
			clear属性:清除浮动
			both:两边都不允许浮动
			left:左边不允许浮动
			right:右边不允许浮动


选择器优先级
行内样式>id选择器>类选择器>元素选择器


无序列表u1
      li列表项
      ype:小圆圈circle,小方块square,默认小黑点disc
有序列表ol
      	常用属性:
      		type:指定序号类型
      		star:从几开始,必须写数字


盒子模型
每个盒子由四个部分组成,其效用由它们各自的边界所定义,
每个盒子四个边界,内容边界content Edge,内边距边界padding Edge
边框边界Border Edge,外框边界Margin Edge
padding-top是指一个元素在内边距区域中上方的高度


行内元素和块级元素的区别
块级元素会独占一行,默认情况下,其宽度自动填满其父元素宽度

块级元素可以设置width,height属性.
块级元素即使设置了宽度,仍然是独占一行.
块级元素可以设置margin和padding属性.
块级元素对应于display:block.
<h1>,<hr>,<p>,<ul>,<table表格>,<ul列表>,<form表单>,<div>等

*p,h1,dt等属于文字类块标签,不能放其他块级元素


行内元素不会独占一行,相邻的行内元素会排列在同一行里,直到一行排不下,才会换行

行内元素设置width,height属性无效，它的长度高度主要根据内容决定.

行内元素的margin和padding属性,水平方向的padding-left,padding-right,
margin-left,margin- right都产生边距效果,但竖直方向的padding-top,
padding-bottom,margin-top,margin-bottom却不会产生边距效果.
<span>,<a链接>,<br换行>,<b加粗>,<img图片>,<select下拉列表>等

*行内块元素:<img><input><td>可以设置宽高和对齐属性
display:inline块转行
display:block行转块
display:inline-block行内转行内块标签

网页从输入网址到渲染完成经历了哪些过程
发送到DNS服务器（解析），并获取域名对应的web服务器对应的ip地址；
与web服务器建立TCP连接（低级协议，高级协议基础）；
浏览器向web服务器发送http请求（高级协议）；
web服务器响应请求，并返回指定url的数据（或错误信息，或重定向的新的url地址）；
浏览器下载web服务器返回的数据及解析html源文件；
生成DOM树，解析css和js，渲染页面，直至显示完成


常见用户界面元素包括
1.用于插入url的地址栏
2.后退和前进按钮
3.书签选项
4.刷新和停止按钮以刷新或停止当前文档的加载
5.主页按钮,将您带到主页
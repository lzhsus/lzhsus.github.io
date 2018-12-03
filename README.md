这是lzhsus的博客
===================================  

1.[这是我使用vue vue-router项目](https://github.com/lzhsus/db)<br /> 
2.[这是我使用静态界面项](https://github.com/lzhsus/iTravel)<br /> 
3.[这是微信小程序项目](https://github.com/lzhsus/wx)<br /> 

##GitHub :star

[https://github.com/lzhsus](https://github.com/lzhsus)
#兼容问题（页面在不同浏览器中可能显示不同）
==========
1.##兼容性
````
  在IE6下 子级的宽度会撑开父级设置好的宽度
  温馨提示：盒模型的计算一定要精确，IE浏览器可能显示不同
  ````

2.##兼容性
  ````
 在IE6中，元素浮动，如果宽度需要内容撑开，
 需要给里面的快元素 添加浮动 才可以
  ````
3.##兼容性
  ````
 在IE6,7下，元素要通过浮动{float：left；}排在同一排，就  需要
  解决：给这个元素都加浮动
  ````
4.##兼容性
  ````
 注意标签的嵌套规则
  ````
5.##兼容性
  ````
 在IE6 下，元素的高度如果小于19px的时候，就会
 当成19px来处理
  解决方法：overflow：hidden；
  ````
5.##兼容性
  ````
 在IE6 下不支持1px的dotted边框样式
  解  决：切背景平铺
````
7.##兼容性
  ````  ````
在IE下大部分兼容性都是因为 haslayout 属性
的触发问题，尽量触发 haslayaout 属性 可以
减少很多IE下兼容性问题
  ````
在IE下父级有边框的时候，子元素的margin会失效
 解决：触发父级 haslayout 属性
  ````
8.##兼容性
  ````
在IE6下双边距bug
 在ie6 块元素 ，有浮动， 有横向 margin的值
的时候，横向的margin的值会夸大两倍
解决：转换为内敛 display：inline；

margin-left 一行中左侧的第一个元素有双边距
margin-right 以行中右侧 的第一个
  ````
9.##兼容性 
   ````
在IE 6 7 下 li 本身没有浮动，li里面的内容有浮动，
li下会产生一个间隙
解决：
 1.给li加浮动
 2. 给li加 vertical-align：top：
 3.在IE 6 最小高度，li的间隙问题共存情况
 加float：left；
  ````
10.##兼容性 
  ````
 当 一行子集的宽度之和父级的宽度相差超过3px，
 或者子级元素不满行的情况的时候，最后一行子级
 的margin-bottom会失效。
  ````
11.##兼容性
  ````
在IE6 下 文字容溢出bug
子元素的宽度和父级的宽度如果相差小于3px的时候，两个浮动元素中间有注释或者内敛元素，就会出现文字溢出，
内敛元素越多，溢出越多
  
解决：用div吧注释的或内联元素抱起来
  ````
12.##兼容性
  ````
在IE下，当浮动元元素素和绝对定位是兄弟关系的时候，
绝对定位会失效
解决：
 不让浮动元素和绝对元素是兄弟关系，用div或者其他标签吧
a边检抱起来
  ````
13.##兼容性
   ````
在IE 6 7下 ，子元素有相对定位，父级overflow抱不住子元素
解决：
 给父级也加相对定位
  ````
14.##兼容性
  ````
在IE6 下，如果决定定位的父级宽高是奇数的时候，
子级元素的right和bottom的值会有1px的偏差
  ````
15.##兼容性
  ````
在IE67下，输入型的表单标签控件上下会有1px的间隙
解决：
给input加浮动
  ````
16.##兼容性
  ````
css hack：
 \9 IE10Z之前的ie浏览器解析代码

+或者* 表示ie7包括7之前的ie浏览器
-表示 ie6包括6之前的ie浏览器

  ````








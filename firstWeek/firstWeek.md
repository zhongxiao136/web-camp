# 第一周（周记）
在训练营的第一周已经过去了，到了总结一周的收获的时间了，在这周，自己不敢说自己学到很多，但在压力下自己还是学到比以前多些的。以下便是自己在一周内所学到的东西：
## 前端
### 前端三剑客
> * HTML是网页内容的载体
> * CSS样式是表现。
> * JavaScript是用来实现网页上的特效效果。
#### HTML的标签
在这周自己重新去看了之前学的HTML的标签，才发现自己已经忘得差不多了。因此自己重新整理了一下之前的笔记，用markdown重新写一遍，自己又重新再慕课网上“制作”网页。标签能够在markdown 上通用，自己之前在markdown 上解决不了的问题通过HTML能够解决。

比之前多学了的是学了表单标签，与用户交互，可以制作一个登陆的网页。如下则是用户输入及传输数据的过程：
> <form    method="post"   action="save.php"><br/>
>&nbsp;&nbsp;&nbsp;&nbsp;&lt;label for="username">用户名:</label><br/>
>&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="username" /><br/>
>&nbsp;&nbsp;&nbsp;&nbsp;<label >for="pass">密码:</label><br/>
>&nbsp;&nbsp;&nbsp;&nbsp;<input type="password" >name="pass" /><br/>
></form>
制定文本框
> <textarea  rows="行数" cols="列数">文本</textarea><br/>

而在使用表单设计调查表时，为了减少用户的操作，使用选择框是一个好主意，html中有两种选择框，即单选框和复选框，两者的区别是单选框中的选项用户只能选择一项，而复选框中用户可以任意选择多项，甚至全选。
> <input   type="radio/checkbox"   value="值"    name="名称"   checked="checked"/>
#### CSS
CSS样式是表现，也就是网页可以通过它变得更加明确醒目。
* CSS全称为“层叠样式表 (Cascading Style Sheets)”，它主要是用于定义HTML内容在浏览器内的显示样式，如文字大小、颜色、字体加粗等。

我了解到CSS样式的表现主要是通过HTML中的&lt;style>标签来实现的，css 样式由选择符和声明组成，而声明又由属性和值组成，如：
> &lt;p style="color:red;font-size:12px">这里文字是红色。&lt;/p>

css有三种样式：内联式css样式（直接写在现有的HTML标签中）；内联式css样式（直接写在现有的HTML标签中）；外部式css样式（写在单独的一个文件中）
* 优先级：内联式 > 嵌入式 > 外部式

css的选择器正在摸索。。。。
#### JavaScript
至于JavaScript，在这周刚刚买完书回来，自己才刚刚开始学，但自己觉得它挺有趣的，还从前面的起源开始就认真的看，觉得起源也有意思。JavaScript的语法我能够从中找到C语言和Java的影子，就有点像是找不同（可能到后面我就不会那么想了，为后面的我抹一把汗）。

目前刚刚学到条件语句（还没学），JavaScript给我的感觉就是很万能，没有那么拘谨，可能是因为它是弱类型语言，驼峰格式的命名在Java中有用到，变量名称也和Java一样，同样可以有$，拼接字符串也和Java差不多。最强大的地方就是定义数据类型了——无论是整数、浮点数、负数、字符串，统统可以用关键字“var”搞定，不得不说牛逼！其他的符号好像都和C语言和Java差不多，暂时就写到这里（其实也就学到这里），继续加油！
### 后台
自己在这一周内，也从零基础开始接触Java，能够写出Hello world的时候自己还高兴的不得了，因为前面的调试环境什么的特别麻烦，调试好多好多才弄好的，之间舍友还帮了我不少忙，大家共同忙活了挺久才搞出的Hello world（感动到想要流泪)。第一次调试环境变量时是在cmd是运行的，学着学着才开始下载eclipse编译java 文件，之间的过程不容易呀......（说多了都是泪）
> public class hello{<br/>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;public static void main(String[] args){<br/>
		System.out.println("Hello world");<br/>
	}<br/>
   }
   
当然，现在可以跟着视频慢慢学了，前面的工作是有点复杂，但之后的学习应该就跟学C语言差不多了（虽然学C一样煎熬），在学习过程中能够找到很多与C语言相同的东西，前面的学习相对轻松一点点。继续努力吧！



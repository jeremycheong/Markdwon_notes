## 换行
直接回车不能换行，  
可以在上一行文本后面补两个空格，  
这样下一行的文本就换行了。

或者就是在两行文本直接加一个空行。

也能实现换行效果，不过这个行间距有点大。  	

---
## 文本
普通文本与单行文本不过多介绍，下面看一下文本块。
###文本块
文本块语法1：每行都缩进一个Tab 或四个空格。	

	欢迎查看
	Jeremy
	编写的Github Markdwon 语法 diff。	
	
文本块语法2：将文本快用三个反引号包裹。
```
欢迎查看
Jeremy
编写的Github Markdwon 语法 diff。
```
**注意：使用每行缩进的方式时，必须与之前的文字进行换行（之前文字结尾必须有一个Tab + 空行，文本块结束后结尾也应如此。）;使用反引号就不需要这些。**
###文字高亮
文字高亮使行内部分文字高亮，使用一对反引号。
语法：
```
`Linux` `Python` `socket`
```
效果如下：
`Linux` `Python` `socket`	

---
## 图片
基本格式：
```
![alt](URL title)
```
alt和title即对应HTML中的alt和title属性（都可省略）：	

- alt 表示图片显示失败时的替换文本
- title 表示鼠标悬停在图片时的显示文本（注意这里要加引号）
- URL 表示图片的URL地址	

**注意：**	
 
* 如果引用本仓库的图片，直接写**相对路径**就可以了；
* 如果引用其他github仓库中的图片，格式为：`仓库地址/raw/分支名/图片路径`
* 如果引用为网络图片，一般建议写成标注格式，将URL地址统一写到文末。	

要将github其他仓库引用与互联网引用分开：
例如，github仓库的图片的网络地址（浏览器中显示的地址）
```
https://github.com/jeremycheong/PersonSensor/tree/master/data/weide
```
截图展示：
![](img/github仓库图片引用.jpg)	
如果直接使用写成：
```
![韦德](https://github.com/jeremycheong/PersonSensor/tree/master/data/weide/10.jpg)
```
结果是不会成功展示图片的。
![韦德](https://github.com/jeremycheong/PersonSensor/tree/master/data/weide/10.jpg)
应当写成
```
![韦德](https://github.com/jeremycheong/PersonSensor/raw/master/data/weide/10.jpg)
```
结果为：
![韦德](https://github.com/jeremycheong/PersonSensor/raw/master/data/weide/10.jpg)	



---
title: markdown基本用法
tags:
  - markdown
  - 博客工具
categories:
  - 技术
date: 2017-10-30 23:55:31
---

标题

两种形式：
1）使用=和-标记一级和二级标题。

一级标题
=========
二级标题
---------

使用#，可表示1-6级标题。

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

ggsdf

区块引用

在段落的每行或者只在第一行使用符号>,还可使用多个嵌套引用，如：

> 区块引用
>> 嵌套引用
>>> 嵌套引用
    
               
               
代码区块

代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如
普通段落：

void main()
{
printf("Hello, Markdown.");
}

代码区块：
    
		void main()
		{
				printf("Hello, Markdown.");
		}
    
 
 
fdf
    

注意:需要和普通段落之间存在空行。

* fslkdjf
* slkdfjkl

* sldkfjlj



+ fslkdjf
+ fsldkfjl
- fslkdfj
- fsldkjfkl
1. sldfkjls
2. flskfjls
3. dslfksdfj
3. sdlfkjslkfj

lsdfjksdf
	sdlfjk
    
    

分割线
***
sfd
---
gsdff
___
分割线最常使用就是三个或以上*，还可以使用-和_。

强调

在强调内容两侧分别加上*或者_，如：

*斜体*，_斜体_
**粗体**，__粗体__

 链接

链接可以由两种形式生成：行内式和参考式。
行内式：

[younghz的Markdown库](http://www.jianshu.com)。

参考式：

[younghz的Markdown库1][1]
[younghz的Markdown库2][2]
[1]:http://www.jianshu.com
[2]:http://www.jianshu.com

 图片

添加图片的形式和链接相似，只需在链接的基础上前方加一个！。

![sdf](http://img02.tooopen.com/images/20151228/tooopen_sy_152967398112.jpg)

![ggg](http://upload-images.jianshu.io/upload_images/259-0ad0d0bfc1c608b6.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

 反斜杠\

相当于反转义作用。使符号成为普通符号。

4.11 符号'`'

起到标记作用。如：

`ctrl+a`

```
ctrl+a
fdg
```

表格

相关代码：

| Tables           | Are           | Cool  |
| -------------  |:-------------:| -----:|
| col 3 is          | right-aligned | $160000 |
| col 2 is           | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

相关代码默认左边：

dog | bird | cat
----|------|----
fooooooo | fooooooo  | fooooooo
bar | bar  | bar
baz | baz  | baz



尝试一下

Chrome下的插件诸如stackedit与markdown-here等非常方便，也不用担心平台受限。
在线的dillinger.io评价也不错
Windowns下的MarkdownPad也用过，不过免费版的体验不是很好。
Mac下的Mou是国人贡献的，口碑很好。
Linux下的ReText不错。

![image](https://airship-lion.github.io/images/1509123167736.jpg)
![image](https://airship-lion.github.io/images/1509125741756.jpg)
![image](https://airship-lion.github.io/images/1509380743583.jpg)
![image](https://airship-lion.github.io/images/1509124759947.jpg)


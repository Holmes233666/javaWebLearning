# JavaWeb学习

## Web前端开发

### Web标准

**Web标准**也称为**网页标准**，由一系列标准组成，大部分由W3C（World Wide Web Consortium，万维网联盟）负责制定。

三个部分的组成：

- HTML：负责网页的**结构**（页面元素和内容）
- CSS：负责网页的**表现**（页面元素的外观 ，位置等页面样式，如：颜色、大小等）
- JavaScript：负责网页的**行为**（交互效果）

Vue3, Ajax是基于JavaScript的框架 

## HTML

### HTML结构+CSS样式

#### 简介

##### HTML概念

HTML（HyperText Markup Language）：超文本标记语言

- 超文本：超出了文本的限制，比普通文本更强大。除了文字信息，还可以定义图片、音频、视频等内容
- 标记语言：由标签“<标签名>”构成的语言
  - HTML标签都是预先定义好的。例如：使用<h1>展示标题，使用<img>展示图片，使用<video>展示视频
  - HTML代码直接在浏览器中运行，HTML由浏览器解析

![image-20241112202030289](https://cdn.jsdelivr.net/gh/Holmes233666/blogImage/img/image-20241112202030289.png)



学习HTML：学习标签

##### CSS概念

CSS（Cascading Style Sheet）：层叠样式表，用于控制页面的样式（表现）

####  快速入门

##### HTML快速入门

编写html的步骤：

- 新建文本文件，后缀名改为.html
- 编写html的基本骨架，定义标题
- 在<body>中填写内容

 ![image-20241112211726225](https://cdn.jsdelivr.net/gh/Holmes233666/blogImage/img/image-20241112211726225.png)

语法特点：

- 标签不区别大小写：`<html> == <Html>== ...`，通常使用全小写
- 属性值可以使用双引号/单引号，通常使用双引号
- HTML的语法结构不严谨：e.g. 如果没有结束标签也没有问题，但是建议规范书写

##### 前端开发工具

Visual Studio Code，主要是用于前端

- 提供了强大的插件库

##### 常见标签&样式

![image-20241121112927482](https://cdn.jsdelivr.net/gh/Holmes233666/blogImage/img/image-20241121112927482.png)

- html解析方式：从上到下逐行解析，所以内容要从上往下编写

编写方式：从上到下编写

- 标题排版

  - 标题标签：`<h1>---<h6>`

  - 超链接：`<a href = "" target = ""> ... </a><a>`

    ![image-20241121114530992](https://cdn.jsdelivr.net/gh/Holmes233666/blogImage/img/image-20241121114530992.png)

    <a>是超链接标签：

    - href：链接地址 - url
    - target：打开方式，包括`_blank`（新窗口打开）和`_self`（本窗口打开（默认））两种方式。

- 标题样式：需要引入CSS样式

  - 行内样式：写在标签的style属性中（配合JavaScript使用）
  - 内部样式：写在style标签中（可以写在页面任何位置，通常约定写在head标签中）
  - 外部样式：写在一个单独的.css文件中（需要通过link标签在网页中引入）

  ![image-20241121150832727](https://cdn.jsdelivr.net/gh/Holmes233666/blogImage/img/image-20241121150832727.png)

三种方式，复用性依次提高。

颜色的表现形式：

![image-20241121152917180](https://cdn.jsdelivr.net/gh/Holmes233666/blogImage/img/image-20241121152917180.png)

- 选择器
- ![image-20241121155826023](https://cdn.jsdelivr.net/gh/Holmes233666/blogImage/img/image-20241121155826023.png)

更多的其他选择器：

![image-20241121160918825](https://cdn.jsdelivr.net/gh/Holmes233666/blogImage/img/image-20241121160918825.png)

 
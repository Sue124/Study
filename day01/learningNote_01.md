# 2018百度前端技术学院——学习笔记01  
学习时间：2018-04-27   
学习目标：学习HTML、CSS、JS基本概念和知识，更深刻地理解前端这一概念。  
最终目标：希望通过这次课程，对web前端相关的知识有一个全面的掌握，多做项目来提升自己。

---  

### 一、HTML  

1. 不同于编程语言，HTML是一种超文本标记语言，可用来描述一个网页的具体内容。  
2. HTML文档也叫web页面，它包含了HTML标签及文本内容。基本结构如下：  
```
　<!DOCTYPE html>                   //声明文档类型
　　<html>                          //<html>标签定义了整个HTML文档   
  　　<head>                        //<head>标签用于定义文档的头部，可引用样式表、提供页面信息等  
 　　　 <meta charset="utf-8">      //文档所使用的字符编码  
　 　　 <title>Hello</title>        //<title>标签定义文档的标题
  　　</head>  
  　　<body>                        //<body>标签定义文档主体，包含文档的所有内容
  　　　<p>Hello world</p>  
　 　 </body>  
  　</html>
  ```  
### 二、CSS  
1. CSS指层叠样式表，定义如何显示HTML元素，为页面添加样式，使其简洁明了。
2. 将页面内容和样式分离开，这样仅需通过编辑CSS文档，便可同时改变站点所有页面的布局和外观。
3. CSS语法规则示例：   

```
　p {color: red;}  
　
　p - 选择符(selector)，通常是需要改变样式的HTML元素。  
　{color: red}- 声明(declaration)，由一个属性和一个值组成。 
　color - 属性(property)，是希望设置的样式属性。  
　red - 值(value)，属性的值。
```
### 三、JavaScript  
1. JavaScript是一种解释性脚本语言，可用来向HTML页面添加交互行为。
2. 通过JavaScript，可为网页添加各种动态功能，使页面更丰富多彩。
2. JavaScript与Java是两种完全不同的语言。

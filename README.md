 # 笔记

 >作者：王
 
 ## HTML 标签
 
 p标签 创建一个文本段落
 ```Python
 <p>这是一个段落</p>
```
p标签的用法 br是换行
 ```Python
<html>
<html>
<head>
<meta charset="utf-8">
<title>W3Cschool教程(w3cschool.cn)</title>
</head>

<body>

<h1>春晓</h1>

<p>
   春眠不觉晓， <br/>
   处处闻啼鸟。<br/>
   夜来风雨声，<br/>
   花落知多少。<br/>
</p>

<p>注意，浏览器忽略了源代码中的排版（省略了多余的空格和换行）。</p>

</body>
</html>
```
#### 效果

![](./image/QQ截图20190511142233.png)

```Python
```
 ## CSS 样式
 
#### 外部样式导入
CSS样式导入
```Python
 <link rel="stylesheet" type="text/css" href="mystyle.css>
```
JS样式导入
```Python
 <link rel="stylesheet" type='text/javascript' href="js/new_file.js" />
```
内联样式
```Python
 <p style="color:sienna;margin-left:20px">这是一个段落。</p>
```

#### width - 宽度
 - width：100%；百分比计算宽度
 - width：100px；像素计算宽度
 - width：100em；对长度单位

#### height - 高度
 - height：100%；百分比计算高度
 - height：100px；像素计算高度
 - height：100em；对长度单位

#### background-color - 背景颜色

 - background-color：#000；

#### background-image - 背景图片

 - background-image：url（图片地址）；

#### background-repeat - 背景平铺方向

 - background-repeat:
 - repeat-x；水平平铺 
 - repeat-y；垂直居中
 - no-repeat；不平铺

#### background-position - 背景图像位置

 - top、bottom、left、right，center；可以使用长度值，如 100px 或 5em
 - background-position：
 - 50% 50%；百分百
 - 50px 50px；像素
 - top；上面
 - bottom；下面
 - left；左边 
 - right；右边
 - center; 居中
 - left top；左上
 - left bottom；左下
 - left center；向左居中
</br> ...

简单书写：body {background:#颜色 url('图片') 平铺 图像位置;} 
```Python
 body {background:#ffffff url('img_tree.png') no-repeat right top;}
```
body {background:#白色 url('图片') 不平铺 向右上;}

#### font-family - 字体

#### margin：0 auto;   //水平居中

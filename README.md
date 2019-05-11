 # 笔记

 >作者：王

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
 - top；上面
 - bottom；下面
 - left；左边 
 - 50% 50%；百分百
 - 50px 50px；像素
 - left top；左上
 - left bottom；左下
</br> ...
 - 简单：body {background:#颜色 url('图片') 平铺 图像位置;} 
```Python
 body {background:#ffffff url('img_tree.png') no-repeat right top;}
```

#### font-family - 字体

#### margin：0 auto;   //水平居中

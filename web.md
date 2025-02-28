# Web常用总结
##### 2025年2月25日 
##### author nullpoga0321
##### 基于小鱼的教材整理
---
## 2.1
HTML标签通常是成对出现的，开始标签和结束标签；
开始标签和结束标签之间的所有代码称为**HTML元素**，<u>标签中的关键词是元素的名称,标签之间的文本就是元素的内容</u>；

**html**元素描述了整个网页的内容
**head**元素是所有头部元素的容器
**title**元素指定了网页的标题
**body**元素包含可见的页面内容
**h1**元素定义了一个大号的标题
**p**元素定义了一个段落

---
## 2.2 img/a 

**img标签**用于向网页嵌入一幅图像,必需属性:
- src 指定待嵌入图像的路径
- alt 指定图像的替代文本（如果图像出于一些原因无法显示会用文本替代）

```html
<img src = 'img/text.png' alt = 'logo' width = '256px' height = '256px'>
```
<br>

**a标签**用于定义超链接，从一个网页跳转到另一个网页:

- href属性 用于指定目标URL
- target属性 指定浏览器在何处打开URL：
    - _blank 在新窗口打开URL
    - _parent 在当前父窗口打开URL
    - _self 在当前窗口打开URL
    - _top 在整个窗口中打开URL
    - _framename 在指定的框架中打开URL
---
## 2.3 meta
#### 2.3.1
声明文档编码，解决乱码问题
```html
<head>
    <title>声明文件编码</title>
    <meta charset='utf-8'>
</head>
```

#### 2.3.2 
网页自动适应终端屏幕的尺寸
```html
<head>
    <title>声明文件编码</title>
    <meta charset='utf-8'>
    <meta name='viewport' content='width=device-width,initial-scale=1.0'>
</head>
```

#### 2.3.3 
搜索引擎优化
```html
<meta name='keywords' content= ' 此处填为搜索引擎提供的网页关键词>
<meta name='description' content= ' 此处填网页描述 '>
<meta name='author' content = '此处填写作者'>
```
#### 2.3.4
网页自动跳转
```html
<meta http-equiv='refresh' content='此处填写等待的时间；此处填写目标地址的代码'>
```

## 2.4 style

用于给HTML文档制定样式信息，有三个属性:
- media 指定样式适用的媒体
- scoped 指定样式的作用范围
- 指定样式的类型

## 2.5 link 

CSS样式可以单独保存为外部文件，然后使用LINK元素将其链接进来

# 3

# 4 

# 5

# 7



---
layout: post
title:  "Markdown 书写格式"
categories: Markdown
tags: Markdown
author: Bliss
---

* content
{:toc}

# 欢迎使用Markdown编辑器

我们对Markdown编辑器进行了一些功能拓展与语法支持，除了标准的Markdown编辑器功能，我们增加了如下几点新功能，帮助你用它写博客：

 1. **全新的界面设计** ，将会带来全新的写作体验；
 2. 在创作中心设置你喜爱的代码高亮样式，Markdown **将代码片显示选择的高亮样式** 进行展示；
 3. 增加了 **图片拖拽** 功能，你可以将本地的图片直接拖拽到编辑区域直接展示；
 4. 全新的 **KaTeX数学公式** 语法；
 5. 增加了支持**甘特图的mermaid语法[^1]** 功能；
 6. 增加了 **多屏幕编辑** Markdown文章功能；
 7. 增加了 **焦点写作模式、预览模式、简洁写作模式、左右区域同步滚轮设置** 等功能，功能按钮位于编辑区域与预览区域中间；
 8. 增加了 **检查列表** 功能。

## 功能快捷键

撤销：<kbd>Ctrl/Command</kbd> + <kbd>Z</kbd>  
重做：<kbd>Ctrl/Command</kbd> + <kbd>Y</kbd>  
加粗：<kbd>Ctrl/Command</kbd> + <kbd>B</kbd>  
斜体：<kbd>Ctrl/Command</kbd> + <kbd>I</kbd>  
标题：<kbd>Ctrl/Command</kbd> + <kbd>Shift</kbd> + <kbd>H</kbd>  
无序列表：<kbd>Ctrl/Command</kbd> + <kbd>Shift</kbd> + <kbd>U</kbd>  
有序列表：<kbd>Ctrl/Command</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd>  
检查列表：<kbd>Ctrl/Command</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd>  
插入代码：<kbd>Ctrl/Command</kbd> + <kbd>Shift</kbd> + <kbd>K</kbd>  
插入链接：<kbd>Ctrl/Command</kbd> + <kbd>Shift</kbd> + <kbd>L</kbd>  
插入图片：<kbd>Ctrl/Command</kbd> + <kbd>Shift</kbd> + <kbd>G</kbd>  


## 合理的创建标题，有助于目录的生成

直接输入1次<kbd>#</kbd>，并按下<kbd>space</kbd>后，将生成1级标题。  
输入2次<kbd>#</kbd>，并按下<kbd>space</kbd>后，将生成2级标题。  
以此类推，我们支持6级标题。有助于使用`TOC`语法后生成一个完美的目录。  



## 如何改变文本的样式

*强调文本* _强调文本_

**加粗文本** __加粗文本__

~~删除文本~~

> 引用文本

H<sub>2<sub>O is是液体。

2<sup>10<sup> 运算结果是 1024.



## 插入链接与图片

链接: [link](https://mp.csdn.net).

图片: ![Alt](https://avatar.csdn.net/7/7/B/1_ralf_hx163com.jpg)

带尺寸的图片: ![Alt](https://avatar.csdn.net/7/7/B/1_ralf_hx163com.jpg=30x30)

居中的图片: ![Alt](https://avatar.csdn.net/7/7/B/1_ralf_hx163com.jpg#pic_center)

居中并且带尺寸的图片: ![Alt](https://avatar.csdn.net/7/7/B/1_ralf_hx163com.jpg#pic_center=30x30)

当然，我们为了让用户更加便捷，我们增加了图片拖拽功能。


## 如何插入一段漂亮的代码片

去[博客设置](https://mp.csdn.net/configure)页面，选择一款你喜欢的代码片高亮样式，下面展示同样高亮的 `代码片`.
```javascript
// An highlighted block
var foo = 'bar';
```


## 生成一个适合你的列表

- 项目
  - 项目
    - 项目

1. 项目1
2. 项目2
3. 项目3

- [ ] 计划任务
- [x] 完成任务


## 创建一个表格
一个简单的表格是这么创建的：

项目     | Value
-------- | -----
电脑  | $1600
手机  | $12
导管  | $1

### 设定内容居中、居左、居右

使用`:---------:`居中  
使用`:----------`居左  
使用`----------:`居右  

| 第一列       | 第二列         | 第三列        |
|:-----------:| -------------:|:-------------|
| 第一列文本居中 | 第二列文本居右  | 第三列文本居左 | 


### SmartyPants
SmartyPants将ASCII标点字符转换为“智能”印刷标点HTML实体。例如：

|    TYPE   |ASCII                          |HTML                         
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## 创建一个自定义列表
Markdown
:  Text-to-HTML conversion tool

Authors
:  John
:  Luke


## 如何创建一个注脚

一个具有注脚的文本。[^2]  

[^2]: 注脚的解释  


##  注释也是必不可少的

Markdown将文本转换为 HTML。  

*[HTML]:   超文本标记语言  


---
title: Markdown 学习笔记
author: Hellen
date: '2018-05-07'
slug: markdown-study-notes
categories:
  - study-notes
tags:
  - tools
---

## 概述
Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。它以纯文本发布，易读易写。语法以少量符号组成，兼容HTML。

中文语法说明请看[这里](https://www.appinn.com/markdown/)。

## 编辑器
- OSX

    VSCode、Atom、Byword、Mou、Typora、MacDown、RStudio
- Linux

    VSCode、Atom、Typora、ReText、UberWriter、RStudio
- Windows

    VSCode、Atom、MarkdownPad、Miu、Typora、RStudio
- ......

我现在用的是

[Visual Studio Code中文版](http://www.downza.cn/soft/198863.html)。

## 常用语法
- 标题 前面加1-6个#分别表示1-6级标题
- 粗体 **你好** \*\*你好\*\* 或 \_\_你好\_\_
- 强调 *你好* \*你好\*或\_你好\_
- 划掉 ~~你好~~  \~\~你好\~\~
- 如果要在文字前后直接插入普通的星号或底线，可以用反斜线 \
- 列表 无序列表前面加*或+或-及空格，有序列表前面加数字.空格。每个列表的段落间空一行。
- 水平分割线 三个及以上的-或*或=

    ===================手动分割线==================
    
- 代码区块 

    `高亮code` 空一行及Tab，代码前后各加`

        底纹code，空一行及Tab（或4个空格）。如果是在列表中，则用两个Tab或8个空格。
```r
library(stringr)  三个`后加编辑语言类型如r,另行code,以另起一行三个`结尾
```
- 引用区块 内容前面加>及空格，嵌入引用再加一个>

    > 实验设计很重要。——Hellen
    >
    >> 世界上有三种谎言：谎言、该死的谎言和统计数据。 ——马克吐温
- 链接

    [你好](https://life2cloud.com/) 【你好](http://aaa.com "optional title"）

    或[你好][id]

    [id]: https://life2cloud.com/

    This is [the same 你好][id].

    或I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

- 插入图片 ![图]()  

  ![图]（./本地图片.jpg）或者![图]（http://）
  
- 插入表格 空行后输入每行内容，中间用|隔开。
第一行为列名，第二行定义表格及对齐方式。-或:-为左对齐，-:为右对齐，:-:为居中对齐。

| 年龄  | 身高  | 体重  |
| :---: | :---: | :---: |
|   1   |   2   |   3   |
|   4   |   5   |   6   |
|   7   |   8   |   9   |






# Welcome to my blog!
✌️ Hello World!\
🧸 这里是我的个人博客。\
通过[这个地址](https://lewisliugl.cn/)可以直接访问。✨
---
## 本站Blog编辑的一些技巧
### 编写摘要
使用<!--more-->在MD文档中进行划分，格式如下：
```markdown
正文的一部分作为摘要
<!-- more -->
余下的正文
```
### 指定文章封面和文章页面顶部大图
单篇文章指定封面图：在文章开头 Front-matter中配置 index_img 属性。
单篇文章指定文章页顶部大图：在文章开头 Front-matter中配置 banner_img 属性。
```markdown
---
title: 文章标题
index_img: /img/index.jpg
banner_img: /img/banner.jpg
date: 2019-10-10 10:00:00
---
以下是文章内容
```
### 指定文章标签
使用tags属性指定文章标签
```markdown
---
title: 文章标题
tags: [ Hexo, Fluid ]
date: 2019-10-10 10:00:00
---
以下是文章内容
```
### 指定文章类别
使用categories属性指定文章类别
```markdown
---
title: 文章标题
categories: 开发工具🔧
date: 2019-10-10 10:00:00
---
以下是文章内容
```
### 在文章中添加tag
```html
<p class="note note-primary">标签</p>
```
一共可以指定7种标签：
- primary 紫
- secondary 灰
- success 绿
- danger 红
- warning 黄
- info 蓝
- light 黑
### 行内标签
```html
<span class="label label-primary">Label</span>
```
一共可以指定6种标签
- primary 紫
- default 灰
- info 蓝
- success 绿
- warning 黄
- danger 红
### 按钮
```markdown
{% btn url, text, title %}
```
- url：链接
- text：按钮上的文本
- title：悬停文字
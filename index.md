---
layout: page
title: Mind in Math
tagline: Bloging my mind
---
{% include JB/setup %}

## 前言

这里是我的个人博客，我在这里发布的都是我随手记下的学习和工作中产生的想法。

我热爱着计算机科学事业，同时也是[自由软件](http://www.fsf.org/)和[RMS](https://stallman.org/)的忠实信徒。但我自认为骨子里仍是一个数学爱好者。

我将博客的主题命名为Mind in Math，一来是为了纪念我与数学的不解之缘，再来就是我作为数学爱好者的一点矜持。博客的内容并不总和数学是有关的，但我希望我多年里培养起来的数学素养，能够让我时常站在数学思想的角度去思考问题。

## 个人简介

**姓名：** | 张静轩（Jensen Zhang）
**邮箱：** | jingxuan.n.zhang@gmail.com
           | fno2010@live.cn
           | 2010\_fno@tongji.edu.cn

### 个人经历

本人系2011级的计算机专业本科生，本科期间曾在数学系就读过，算起来也可以说是半个数学系的人。

时间            | 经历
----------------|------------------
2011.9 - 2013.2 | 同济大学数学系
2013.2 -        | 同济大学计算机系

---

我曾接触和从事过的领域并不算很宽泛，大都围绕着数学和计算机而开展的，其中包括：

* 应用数学
    - 课题：物体承载能力与承载面的作用关系
    - 数学建模：交通流量预测模型/运动员能力综合评价模型
* 应用计算机
    - 神经网络方法实现基于Wifi的室内区域定位
    - SVM与Word2Vec构建中文短文本情感极性分类模型
    - 基于数字水印与分布式RFID的电子标签防伪
* 编程开发
    - Web平台在线编程
    - 在线图像处理平台
* 计算机系统
    - 组合逻辑多周期MIPS指令集CPU设计
    - seL4微内核平台移植与相关研究

## 博客列表

近期发表的博客：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 鸣谢

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

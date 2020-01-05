---
# 技术文档之总结说明

* [Pythonanywhere部署网址](http://carlalyz.pythonanywhere.com/)
* [GitHub的URL](https://github.com/Carlalyz/flask)

本项目使用Python搭建Flask网站

---

# HTML档描述

整个Flask网站共有5个页面url，其中“/hurun”包含4个子主题url：

### 首页
- 主页为《故事说明-中国发展与人民共享》的故事主要内容。
- 首页的上方有一个单选选择器，其中有“居民消费水平”、“人均GDP与消费水平”、“GDP水平情况”、“分省人均GDP”四个选项，点击其中一个选项然后点击“Do it”即可跳转到其相关图标和表格的页面

### 子页面
- 四个子页面分别对应“居民消费水平”、“人均GDP与消费水平”、“GDP水平情况”、“分省人均GDP”的交互数据图表和该区块文字内容。
- 界面分布是相应的数据交互图和相对应的表格数据以及相应的文字介绍

### 数据交互图页面
- 数据交互图页面数据内容有数据交互图和相应的文字介绍

---

# Python档描述

### 概括
- flask文件夹里面有.idea文件夹、__pycache__文件夹（module）、templates文件夹(主要html集合)、app.py文件以及各类数据文档

### app.py
- 运用到列表循环，for循环等等
- 运用到数据结构嵌套适合在子页面中嵌套出现数据交互图和数据图表
- 利用推导式使得在子页面中进行不同html的跳转
- 利用判断语句判断用户点击的是什么从而跳转到相应界面
- 在python档中赋予不同html文件不同的跳转地址并且开展出不同功能，实现python文档与html文档的数据交互

---

# web app 动作描述
- 主页面的上方有一个单选选择器，选择不同的选项然后点击下拉框下面的“Do it”即可跳转到四个不同的子页面
- 图表可以根据选择关闭相应可视数据

### 实现数据交互，可以在页面进行精确转换
- 是否含有复杂数据结构的列表循环


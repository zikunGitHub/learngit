---
date: 2016-12-14 16:36
status: public
title: DOM--获取元素
---

# document 核心对象
> document 是核心对象 对元素的样式、内容、位置进行操作。
* 文档树模型(节点)
## 获取元素
* document.getElementById();   Dom对象
* document/obj.getElementsByTagName();   Dom元素集合
* document/obj.getElementsByClassName();   Dom元素集合   兼容性问题
* document.getElementsByName();   Dom元素集合
* document.URL 只能获取，不能赋值
* document.title 获取当前文档的标题
## Dom集合
* document.all     文档所有元素的集合
* document.forms   文档form的集合
* document.anchors 文档锚链接的集合
* document.images 文档所有图片的集合
* document.links  文档所有链接的集合
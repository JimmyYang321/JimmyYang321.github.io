---
layout: default
title: 首页
---

# 嵌入式全栈技术博客

> 记录嵌入式开发中的底层原理、驱动、协议与系统设计。

---

## 分类

- [Linux 内核](/categories/linux/)
- [驱动开发](/categories/driver/)
- [通信协议](/categories/protocol/)
- [V4L2 / 媒体](/categories/v4l2/)
- [PCIe / 高速接口](/categories/pcie/)
- [工具链 / 构建](/categories/toolchain/)

---

## 最新文章

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

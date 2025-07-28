---
layout: home
title: yikemango
permalink: /
---

歡迎來到我的筆記站 ✨
這裡是我邁向自由工作者的奮鬥紀錄 📓

---

## 最新文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
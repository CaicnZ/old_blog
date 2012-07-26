---
layout: page
title: Howe Isamu
tagline: 
---
{% include JB/setup %}

我是 Howe Isamu 这是我的记忆之书，它使用jekyll部署在github pages并使用cloudflare加速。

在这我会把一些值得记录的东西留下来，并不想它消失在信息的洪流中去。回到旧时光吧，my dear~

#### 最近发布的文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

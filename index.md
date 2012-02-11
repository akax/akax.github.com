---
layout: page
title: باش بەت
---
{% include JB/setup %}


بلوگ خاتىرىسى :

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date: "%Y-%m-%d :يوللانغان ۋاقىت" }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




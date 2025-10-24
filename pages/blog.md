---
layout: default
title: "Blog"
permalink: "blog"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color: gray;"> - {{ post.author }}</span>
    </li>
  {% endfor %}
</ul>

---
layout: blog
title: Blog
permalink: /blog/
---

Here I collect the out stream of the rare event of writing. Enjoy! 

<ul>
  {% for post in site.blog.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
---
layout: default
title: "Posts"
---

# Recent Posts
<!--
[Example post](/jekyll/update/2018/09/06/welcome-to-jekyll.html)

[First post](/2019/08/23/test-post.html)
-->
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
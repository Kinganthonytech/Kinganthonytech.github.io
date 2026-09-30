---
layout: default
title: Blog
---

# Writing

{% assign ordered = site.posts | sort: "url" %}
<ul>
{% for post in ordered %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

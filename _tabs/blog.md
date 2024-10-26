---
layout: page
title: Blog
icon: fas fa-blog
order: 1
---

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

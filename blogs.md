---
layout: default
title: "Blog Posts"
permalink: /blogs/
---

# Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})  
  <small>Published on {{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}


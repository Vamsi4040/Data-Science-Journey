---
layout: default
title: "Blog Posts"
permalink: /blogs/
---

# Blog Posts

{% if site.posts.size > 0 %}
  {% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})  
    <small>Published on {{ post.date | date: "%B %d, %Y" }}</small>
  {% endfor %}
{% else %}
  No blog posts found.
{% endif %}


---
title: Posts
layout: posts_layout
---



{% assign sorted = site.posts | sort: date %}
{% for post in sorted %}



## {{ post.title }} ### - {{ post.date }}

{% endfor %}

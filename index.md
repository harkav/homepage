---
layout: home
title: My homepage
---

Welcome to my blog! 

{% for post in site.posts %}
  <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
  <p>{{ post.excerpt }}</p>
{% endfor %}

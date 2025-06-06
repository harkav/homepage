---
layout: home
title: My homepage
---

[Picture of Finse](/assets/finse.jpg)

Welcome to my blog! 

{% for post in site.posts %}
  <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
  <p>{{ post.excerpt }}</p>
{% endfor %}

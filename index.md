---
layout: home
title: My homepage
---

Welcome to my blog! 


<a href="{{ site.baseurl }}/about/" style="display: inline-block; padding: 0.5em 1em; background-color: #007acc; color: white; border-radius: 4px; text-decoration: none;">About Me</a>


{% for post in site.posts %}
  <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
  <p>{{ post.excerpt }}</p>
{% endfor %}

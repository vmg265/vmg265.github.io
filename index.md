---
layout: default
---

# Welcome to My Blog

Here are my latest posts:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}

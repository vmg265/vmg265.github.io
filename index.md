---
layout: default
---

# Welcome to My Blog

Here are my latest posts:

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

---

*Writing about what I find and love*

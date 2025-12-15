---
layout: default
title: Home
---

# {{ site.title }}

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{{ post.description }}

---
{% endfor %}

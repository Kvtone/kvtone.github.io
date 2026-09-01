---
layout: default
---

# My Blog

Welcome to my blog.
[Engine sim](./rocket-engine/)

## Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %-d, %Y" }}

{{ post.excerpt }}

{% endfor %}

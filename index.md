---
layout: default
---

# My Blog

Welcome to my blog.

Link to Engine sim [View my project](./project.md)
[Visit my website](https://kvtone.github.io/rocket-engine/)

## Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %-d, %Y" }}

{{ post.excerpt }}

{% endfor %}

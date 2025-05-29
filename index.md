---
layout: default
---

# Welcome to my AI journey blog!

A running record of my experience using AI 

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

[Read more →]({{ post.url }})

---
{% endfor %}
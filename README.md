---
permalink: /
layout: main.html
---
# mon blog 

## mes posts
{% for post in collections.posts %}
- [{{post.data.title}}]({{post.url | url }})
{% endfor %}

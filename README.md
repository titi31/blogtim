---
permalink: /blogtim/
layout: main.html
---
# mon blog 

## mes posts
{% for post in collections.posts %}
- [{{post.data.title}}]({{/blogtim/post.url }})
{% endfor %}

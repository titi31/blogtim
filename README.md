---
permalink: /
layout: main.html
---
# [center]le blog de timothé [/center] 

## [center] mes posts [/center]
{% for post in collections.posts %}
- [center] [{{post.data.title}}]({{post.url | url }})[/center]
{% endfor %}

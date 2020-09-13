---
permalink: /
layout: main.html
---
# le blog de timothé 

## mes posts 
{% for post in collections.posts %}
 - [{{post.data.title}}]({{post.url | url }})
{% endfor %}

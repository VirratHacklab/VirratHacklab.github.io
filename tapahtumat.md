---
layout: hacklab
title: Tapahtumat
---

{% for post in site.posts %}
    {% if post.categories contains 'event' %}
* [{{ post.title }}]({{ post.url }})
    {% endif %}
{% endfor %}
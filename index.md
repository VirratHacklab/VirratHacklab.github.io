---
layout: hacklab
title: Ajankohtaista
---

## [](#header-2)Uusimmat tapahtumat

{% for post in site.posts %}
    {% if post.categories contains 'event' %}
* [{{ post.title }}]({{ post.url }})
    {% endif %}
{% endfor %}

## [](#header-2)Uusimmat blogikirjoitukset

Tulossa

## [](#header-2)Ajankohtaiset kerhot

Tulossa

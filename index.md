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

{% for post in site.posts %}
    {% if post.categories contains 'blog' %}
* [{{ post.title }}]({{ post.url }})
    {% endif %}
{% endfor %}

## [](#header-2)Kerhouutiset

{% for post in site.posts %}
    {% if post.categories contains 'club' %}
* [{{ post.title }}]({{ post.url }})
    {% endif %}
{% endfor %}

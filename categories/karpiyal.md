---
layout: page
title: கற்பியல்
permalink: /karpiyal/
---

#### The Post-marital love

{% assign work_items = site.categories.karpiyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}

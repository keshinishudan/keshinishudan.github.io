---
layout: page
title: களவியல்
permalink: /kalaviyal/
---

#### The Pre-marital love

{% assign work_items = site.categories.kalaviyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}


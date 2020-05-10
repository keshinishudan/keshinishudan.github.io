---
layout: page
title: துறவறவியல்
permalink: /thuravaraviyal/
---

#### Ascetic Virtue

{% assign work_items = site.categories.thuravaraviyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}


---
layout: page
title: அமைச்சியல்
permalink: /amaichiyal/
---

####  Ministers of state

{% assign work_items = site.categories.amaichiyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}


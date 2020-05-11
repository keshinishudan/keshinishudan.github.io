---
layout: page
title: ஒழிபியல்
permalink: /olipiyal/
---

#### Miscellaneous (Appendix)

{% assign work_items = site.categories.olipiyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}


---
layout: page
title: பாயிரவியல்
permalink: /paayiraviyal/
---

#### Paayiraviyal

|**பாயிரவியல்**| **Introduction** |
|---------------|
{% assign work_items = site.categories.paayiraviyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.title }}**]({{post.url}})|[{{post.title-en}}]({{post.url}})|
{% endfor %}
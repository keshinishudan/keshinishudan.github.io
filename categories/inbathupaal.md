---
layout: page
title: காமத்துப்பால்
permalink: /inbathupaal/
---

### Love

#### The Pre-marital love

{% assign work_items = site.categories.kalaviyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}
****

#### The Post-marital love

{% assign work_items = site.categories.karpiyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}
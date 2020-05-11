---
layout: page
title: அறத்துப்பால்
permalink: /arathupaal/
---
### Virtue

#### Introduction

{% assign work_items = site.categories.paayiraviyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}
****

#### Domestic Virtue

{% assign work_items = site.categories.illaraviyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}
****

#### Ascetic Virtue

{% assign work_items = site.categories.thuravaraviyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}

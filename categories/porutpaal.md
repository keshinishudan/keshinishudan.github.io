---
layout: page
title: பொருட்பால்
permalink: /porutpaal/
---
### Wealth

#### Royalty

{% assign work_items = site.categories.arasiyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}
****

####  Ministers of state

{% assign work_items = site.categories.amaichiyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}
****

#### The Essentials of a State

{% assign work_items = site.categories.angaviyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}
****

#### Miscellaneous (Appendix)

{% assign work_items = site.categories.olipiyal | sort: 'absno' -%}
{%- for post in work_items -%}
[**{{ post.title }}**]({{post.url}})<br>
[{{post.title-en}}]({{post.url}})

{% endfor %}


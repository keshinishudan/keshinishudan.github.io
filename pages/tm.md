---
layout: page
title: Thiruvalluva Maalai
permalink: /thiruvalluva-maalai/
redirect_from:
  - /tm/
---

### திருவள்ளுவமாலை

{% assign work_items = site.categories.tm | sort: 'tmno' -%}
{%- for post in work_items -%}
[**{{post.tmno}}&nbsp;{{ post.title }}**]({{post.url}})<br>
[{{post.author}}]({{post.url}})

{% endfor %}
 

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

##### குறிப்புகள்
> [திருக்குறள் - தமிழ்மரபுரை - தேவநேயன் எழுதியது](http://www.tamilvu.org/library/l2100/html/l2100vur.htm){:rel="nofollow"}

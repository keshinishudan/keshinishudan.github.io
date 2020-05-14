---
layout: page
title: kural
permalink: /kural/
---

{% assign seetharam = site.kural | sort: "abskno" %}
{% for kural in seetharam %}

<a href="{{ kural.url }}">
  {{ kural.title }} - {{ kural.kuralno }}
</a>

{% endfor %}

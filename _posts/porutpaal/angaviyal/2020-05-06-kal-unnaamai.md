---
layout: kural
title: "கள்ளுண்ணாமை"
date: 2020-05-06 08:05:05 +0530
categories: [porutpaal, angaviyal]
permalink: /93/kal-unnaamai/
athigaram: "93"
absno: "093"
athigaram-en: Kal Unnaamai
title-en: Not Drinking Palm-Wine
redirect_from:
  - /93/
description: Read Kal Unnaamai from porutpaal, angaviyal titled Not Drinking Palm-Wine கள்ளுண்ணாமை
---

## {{page.title-en}} <sup><a href="#transliteration">{{page.athigaram}}</a></sup>

{% for kl in site.data.kural %}
{% if kl.athigaram == page.athigaram %}

###### [{{kl.no}}](/kural/{{ kl.no | strip }})

<h4> {{kl.kural | lstrip | newline_to_br}} </h4> 
 
> {{kl.pope | lstrip | newline_to_br }} 

{{kl.moova}} 

> {{kl.popemean}} 

{% if kl.pa %}
<details>
  <summary > பரிமேலழகர் உரை </summary>
      {{kl.pa | replace: "விளக்கம்", "<br><strong><em>  விளக்கம்: </em></strong><br>" }}
</details>
{% endif %}

{% if kl.mk %}
<details>
  <summary > மணக்குடவர் உரை </summary>
      {{kl.mk | replace:"(இ - ள்.)","<strong><em>(இதன் பொருள்)</em></strong>" | replace:"(எ - று)","<br><strong><em>(என்றவாறு)</em></strong>"}}
</details>
{% endif %}

{% endif %}
{% endfor %}

<br>
<details class = "trans">
<summary id="transliteration"> transliteration</summary>

{%- for kl in site.data.kural -%}
{%- if page.athigaram == kl.athigaram -%} 

<p>{{kl.number}} {{kl.transliteration | newline_to_br}}</p>

{%- endif -%}
{%- endfor -%}

</details>
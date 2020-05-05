---
layout: kural
title: "மன்னரைச் சேர்ந்தொழுதல்"
date: 2020-05-04 14:30:21 +0530
categories: [porutpaal, amaichiyal]
permalink: /70/mannaraich-saerndtholugal/
athigaram: "70"
absno: "070"
athigaram-en: Mannaraich Saerndtholugal
title-en: Conduct in the Presence of the King
redirect_from:
  - /70/
description: Read Mannaraich Saerndtholugal from porutpaal, amaichiyal titled Conduct in the Presence of the King மன்னரைச் சேர்ந்தொழுதல்
---

## {{page.title-en}} <sup><a href="#transliteration">{{page.athigaram}}</a></sup>

{% for kl in site.data.kural %}
{% if kl.athigaram == page.athigaram %}

###### {{kl.no}}

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
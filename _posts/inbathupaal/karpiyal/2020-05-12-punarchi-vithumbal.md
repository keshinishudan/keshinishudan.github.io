---
layout: kural
title: "புணர்ச்சிவிதும்பல்"
date: 2020-05-12 09:19:15 +0530
categories: [inbathupaal, karpiyal]
permalink: /129/punarchi-vithumbal/
athigaram: "129"
absno: "129"
athigaram-en: Punarchi Vithumbal
title-en: Desire for Reunion
redirect_from:
  - /129/
description: Read Punarchi Vithumbal from inbathupaal, karpiyal titled Desire for Reunion புணர்ச்சிவிதும்பல்
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
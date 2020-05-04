---
layout: kural
title: "காலமறிதல்"
date: 2020-05-02 02:30:11 +0530
categories: [porutpaal, arasiyal]
permalink: /49/kaalamarithal/
athigaram: "49"
absno: "049"
athigaram-en: Kaalamarithal
title-en: Knowing the fitting Time
redirect_from:
  - /49/
description: Read Kaalamarithal from porutpaal, arasiyal titled Knowing the fitting Time காலமறிதல்
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
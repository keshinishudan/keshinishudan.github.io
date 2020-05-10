---
layout: kural
title: "தகையணங்குறுத்தல்"
date: 2020-05-10 01:53:59 +0530
categories: [inbathupaal, kalaviyal]
permalink: /109/thagaiyanangkuruthal/
athigaram: "109"
absno: "109"
athigaram-en: Thagaiyanangkuruthal
title-en: Mental Disturbance caused by the Beauty of the Princess
redirect_from:
  - /109/
description: Read Thagaiyanangkuruthal from inbathupaal, kalaviyal titled Mental Disturbance caused by the Beauty of the Princess தகையணங்குறுத்தல்
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
---
layout: kural
title:  "கடவுள் வாழ்த்து"
date:   2020-04-12 07:37:25 +0530
categories: [arathupaal, paayiraviyal]
permalink : /1/kadavul-vaazlthu
athigaram : "1"
athigaram-en : Kadavul Vaazlthu
---

##  Kadavul Vaazlthu

{% for kl in site.data.kural %}
{% if kl.athigaram == page.athigaram %}  

###### {{kl.no}}

<h4> {{kl.kural | lstrip | newline_to_br}} </h4> 
 

<br>
{% endif %}
{% endfor %}
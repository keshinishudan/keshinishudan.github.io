---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: thome
---
## Thirukkural
### **அறத்துப்பால் - Virtue**

|**பாயிரவியல் - Introduction** |
|---------------|
{% assign work_items = site.categories.paayiraviyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

|**இல்லறவியல் - Domestic Virtue**|
|---------------|
{% assign work_items = site.categories.illaraviyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

|**துறவறவியல் - Ascetic Virtue**|
|---------------|
{% assign work_items = site.categories.thuravaraviyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}


### **பொருட்பால் - Wealth**

|**அரசியல் - Royalty** |
|---------------|
{% assign work_items = site.categories.arasiyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

|**அமைச்சியல் - Ministers of state** |
|---------------|
{% assign work_items = site.categories.amaichiyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

|**அங்கவியல் - The Essentials of a State** |
|---------------|
{% assign work_items = site.categories.angaviyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

|**ஒழிபியல் - Miscellaneous (Appendix)** |
|---------------|
{% assign work_items = site.categories.olipiyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

### **இன்பத்துப்பால் - Love**

|**களவியல் - The Pre-marital love** |
|---------------|
{% assign work_items = site.categories.kalaviyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

|**கற்பியல் - The Post-marital love** |
|---------------|
{% assign work_items = site.categories.karpiyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}
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

|**அமைச்சியல் - Amaichiyal** |
|---------------|
{% assign work_items = site.categories.amaichiyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

|**அங்கவியல் - Angaviyal** |
|---------------|
{% assign work_items = site.categories.angaviyal | sort: 'absno' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}
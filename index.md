---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: thome
---

## **அறத்துப்பால் - Virtue**

|**பாயிரவியல் - Introduction** |
|---------------|
{% assign work_items = site.categories.paayiraviyal | sort: 'athigaram' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor %}

|**இல்லறவியல் - Domestic Virtue**|
|---------------|
{% assign work_items = site.categories.illaraviyal | sort: 'athigaram' -%}
{%- for post in work_items -%}
|[**{{ post.athigaram}} &nbsp; {{ post.title }}**]({{post.url}})|
|[*{{post.title-en}}*]({{post.url}})|
{% endfor -%}
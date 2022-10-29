---
layout: summary
title: summary
---

{% for suma in site.summary %}
- [{{ suma.date | date : "%F" }}  {{ suma.title }}]({{site.url}}{{site.baseurl}}{{suma.url}}) 
{% endfor %}
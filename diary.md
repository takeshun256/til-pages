---
layout: diary
title: diary
---

{% for dia in site.diary %}
- [{{ dia.date | date : "%F" }}  {{ dia.title }}]({{site.url}}{{site.baseurl}}{{dia.url}}) 
{% endfor %}
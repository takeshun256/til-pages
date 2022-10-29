---
layout: summary
title: summary
---

# 勉強用要約一覧

{% for suma in site.summary %}
- [{{ suma.date | date : "%F" }}  {{ suma.title }}]({{site.url}}{{site.baseurl}}{{suma.url}}) 
{% endfor %}
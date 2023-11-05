---
layout: page
title: Writing
permalink: /writing/
---

#### Writing by the artist | [Writing about the artist]({{site.baseurl}}{% link writing-about.md %}) 
<br>
{% assign writing = site.writing | sort: "year" | reverse %}
{% assign cur_year = writing[0].year %}
## {{cur_year}}
{% for writing in writing %}
  {% if cur_year != writing.year %}
    {% assign cur_year = writing.year %}
<br>
## {{cur_year}}
  {% endif %}
##### [{{writing.title}}]({{site.baseurl}}{{writing.url}})
{% endfor %}

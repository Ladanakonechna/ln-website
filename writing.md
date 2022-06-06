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
{% for text in writing %}
  {% if cur_year != text.year %}
    {% assign cur_year = text.year %}
<br>
## {{cur_year}}
  {% endif %}
##### {{text.title}}[ >>]({{site.baseurl}}{{text.url}})
{% endfor %}

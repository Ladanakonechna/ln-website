---
layout: exhibitions
title: Exhibitions
permalink: /exhibitions-list
---

#### [Gallery view]({{site.baseurl}}{% link exhibitions.md %}) | List view
<br>
{% assign exhibitions = site.exhibitions | sort: "year" | reverse %}
{% assign cur_year = exhibitions[0].year %}
## {{cur_year}}
{% for exhibition in exhibitions %}
  {% if cur_year != exhibition.year %}
    {% assign cur_year = exhibition.year %}
<br>
## {{cur_year}}
  {% endif %}
##### [{{exhibition.title}}]({{site.baseurl}}{{exhibition.url}})
{% endfor %}

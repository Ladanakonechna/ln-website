---
layout: page
title: Works
permalink: /works-list
---

### [Gallery view]({{site.baseurl}}{% link works.md %}) | List view
{% assign works = site.works | sort: "year" | reverse %}
{% assign cur_year = works[0].year %}
## {{cur_year}}
{% for work in works %}
  {% if cur_year != work.year %}
    {% assign cur_year = work.year %}
<br>
## {{cur_year}}
  {% endif %}
##### {{work.title}}[>>]({{site.baseurl}}{{work.url}})
{% endfor %}
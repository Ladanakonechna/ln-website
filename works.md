---
layout: page
title: Works
permalink: /works
---
## List view / [Gallery view]({{site.baseurl}}{% link gallery.md %})
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

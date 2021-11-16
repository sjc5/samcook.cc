---
permalink: /tags/
description: All tags
layout: layouts/other.njk
title: Tags
section: Blog
---

## Tags

{% set myTags = collections.tagList | sort %}

<ul id="all-tags-list">
{% for tag in myTags | filterTagList %}
  {% set tagUrl %}/tags/{{ tag | slug }}/{% endset %}
  <li><a href="{{ tagUrl | url }}"><span class="hashtag">#</span>{{ tag }}</a></li>
{% endfor %}
</ul>

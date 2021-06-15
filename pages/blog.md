---
layout: layouts/home.njk
permalink: /blog/
description: sjc's blog
eleventyNavigation:
  key: Blog
  order: 4
title: Archive
section: Blog
---

## Archive

{% set postslist = collections.posts %}
{% include "postslist.njk" %}

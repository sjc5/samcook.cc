---
layout: layouts/home.njk
permalink: /subscribe/
description: Subscribe to sjc's blog
title: Subscribe
section: Blog
---

## Subscribe

Enter your email below to subscribe to the blog:

<form action="https://buttondown.email/api/emails/embed-subscribe/sjc" method="post" target="popupwindow" onsubmit="window.open('https://buttondown.email/sjc', 'popupwindow')">
  <input type="email" name="email" placeholder="your@email.com" />
  <input type="hidden" value="1" name="embed" />
  <input type="submit" value="SUBMIT" class="button" />
</form>

Alternatively, you can subscribe via <a href="{{ "/feed/feed.xml" | url }}" target="_blank">RSS</a>.

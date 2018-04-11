---
layout: page
title: "blog"
author: Till Grallert
date: 2016-04-16
---

## recent posts:

<ul class="post-list">
{% for post in site.categories['blog'] %}
  {% include post-list-item.html %}
{% endfor %}
</ul>

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

---
layout: page
title: "releases"
author: Till Grallert
date: 2016-04-16 16:05:51 GMT+3
---

There is no proper release schedule yet but I conceive of version 1.0 as the first complete edition. 

- version 0.1 shall be the first "official" release. It is scheduled for May/June 2016 and will include
    1. TEI files of all at least one volume of *al-Muqtabas* (i.e. 12 issues / files) with structural mark-up of mastheads, sections, articles, and with page breaks linked to the facsimiles; for no other reason but interes in their content, we have started work on vol. 5 and 6, which are therefore the most likely release candidates;
    2. MODS / BibTeX files for all issues, sections, and articles;
    3. XSLT stylesheets for all necessary initial and periodic conversions;
    4. XSLT, JS, and CSS for a webview.
- versions 0.1 - 0.x: each completed volume of 11 to 12 issues / TEI files will warant an incremental release.
- version 1.0 shall include
    1. TEI files of all 96 issues of *al-Muqtabas* with structural mark-up of mastheads, sections, articles, and with page breaks linked to the facsimiles;
    2. all the components of version 0.1

## recent releases:

  <ul class="post-list">
    {% for post in site.categories['releases'] %}
      {% include post-list-item.html %}
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

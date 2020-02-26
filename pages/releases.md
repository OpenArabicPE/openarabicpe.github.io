---
layout: page
title: "releases"
author: Till Grallert
date: 2016-04-16 16:05:51 GMT+3
---

There is no proper release schedule for any of the editions (currently we work on two journals from Cairo and Damascus, *al-Muqtabas* and *al-Ḥqāʾiq*) produced by OpenArabicPE but I conceive of version 1.0 as the first complete edition.

- version 0.1 shall be the first "official" release. It includes
    1. TEI files of all at least one volume of *al-Muqtabas* or *al-Ḥaqāʾiq* (i.e. 12 issues / files) with structural mark-up of mastheads, sections, articles, and with page breaks linked to the facsimiles; for no other reason but interes in their content, we have started work on vol. 5 and 6, which are therefore the most likely release candidates;
    2. MODS / BibTeX files for all issues, sections, and articles;
    3. XSLT stylesheets for all necessary initial and periodic conversions;
    4. XSLT, JS, and CSS for a webview.
- versions 0.1 - 0.x: each completed volume of 11 to 12 issues / TEI files will warant an incremental release.
- version 1.0 shall include
    1. TEI files of all issues of *al-Muqtabas* or *al-Ḥaqāʾiq* with structural mark-up of mastheads, sections, articles, and with page breaks linked to the facsimiles;
    2. all the components of version 0.1

## recent releases:

The following list of blog short blog posts includes releases from full editions and smaller projects, such as generated bibliographic metadata for various periodicals, as well as notes for the release tools and schema files.

<div class="posts-list">
{% for post in site.categories['releases'] %}
  {% for post in paginator.posts %}
  <article class="post-preview">
    <a href="{{ post.url | relative_url }}">
      <h2 class="post-title">{{ post.title | markdownify }}</h2>

      {% if post.subtitle %}
      <h3 class="post-subtitle">
        {{ post.subtitle | markdownify }}
      </h3>
      {% endif %}
    </a>

    <p class="post-meta">
      Posted on {{ post.date | date: site.date_format }}
    </p>

    <div class="post-entry-container">
      {% if post.image %}
      <div class="post-image">
        <a href="{{ post.url | relative_url }}">
          <img src="{{ post.image | relative_url }}">
        </a>
      </div>
      {% endif %}
      <div class="post-entry">
        {{ post.excerpt | strip_html | xml_escape | truncatewords: site.excerpt_length }}
        {% assign excerpt_word_count = post.excerpt | number_of_words %}
        {% if post.content != post.excerpt or excerpt_word_count > site.excerpt_length %}
          <a href="{{ post.url | relative_url }}" class="post-read-more">[Read&nbsp;More]</a>
        {% endif %}
      </div>
    </div>

    {% if post.tags.size > 0 %}
    <div class="blog-tags">
      Tags:
      {% if site.link-tags %}
      {% for tag in post.tags %}
      <a href="{{ '/tags' | relative_url }}#{{- tag -}}">{{- tag -}}</a>
      {% endfor %}
      {% else %}
        {{ post.tags | join: ", " }}
      {% endif %}
    </div>
    {% endif %}

   </article>
  {% endfor %}
{% endfor %}
</div>

{% if paginator.total_pages > 1 %}
<ul class="pager main-pager">
  {% if paginator.previous_page %}
  <li class="previous">
    <a href="{{ paginator.previous_page_path | relative_url }}">&larr; Newer Posts</a>
  </li>
  {% endif %}
  {% if paginator.next_page %}
  <li class="next">
    <a href="{{ paginator.next_page_path | relative_url }}">Older Posts &rarr;</a>
  </li>
  {% endif %}
</ul>
{% endif %}

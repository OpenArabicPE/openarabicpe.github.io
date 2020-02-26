---
layout: post
title: "How to search digital muqtabas"
author: Till Grallert
date: 2016-04-16 19:12:00 +0300
categories:
- blog
- workflow
tags:
- webview
- search
- how to
---

User will, of course, want to search the edition for specific terms and will immediately recognise the lack of a dedicated search field in the webview. But behold, individual issues can be searched through the built-in search function in browsers; just hit `ctrl+f` (windows) or `cmd+f` (macintosh) to search individual periodical issues for literal strings. To search across the entire periodical, there are three instantly available options:

- the [GitHub repository](https://github.com/tillgrallert/digital-muqtabas), which allows for browsing and searching and displays search results in context.

![Search the GitHub repository](/assets/images/search-github.jpg)

- Google's web search provides a [`site:` operator](https://moz.com/blog/25-killer-combos-for-googles-site-operator) that can be extensively manipulated:
    + [`site:https://github.com/tillgrallert/digital-muqtabas/blob/master search string`](site:https://github.com/tillgrallert/digital-muqtabas/blob/master) will search all files in the Digital Muqtabas repository.
    + add [`filetype:xml`](site:https://github.com/tillgrallert/digital-muqtabas/blob/master filetype:xml) to search only XML files. Other options would be `filetype:md` for plain text markdown files, `filetype.bib` for BibTeX files etc.

![Search Google with the `site:` operator](/assets/images/search-google.jpg)

- a public [Zotero group](https://www.zotero.org/groups/digital-muqtabas/items/) comprising bibliographic metadata for all articles and sections, including author names, titles, publication dates, volume and issue numbers etc., including links to the webview.
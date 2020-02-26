---
layout: page
title: "How to search"
author: Till Grallert
date: 2020-02-27
categories:
- blog
- workflow
tags:
- webview
- search
- how to
---

Users will, of course, want to search the edition for specific terms and will immediately recognise the lack of a dedicated search field in the webview. But behold, individual issues can be searched through the built-in search function of your browser. Just hit `ctrl+f` (windows) or `cmd+f` (macintosh) to search individual periodical issues for literal strings. To search across an entire periodical or the whole corpus, there are three instantly available options:

1. Search the GitHub repository of the periodical you are interested in, such as [*al-Muqtabas*](https://github.com/tillgrallert/digital-muqtabas). This allows for browsing and searching and displays search results in context.

    ![Search the GitHub repository](/assets/images/search-github.jpg)

2. Google's web search provides a [`site:` operator](https://moz.com/blog/25-killer-combos-for-googles-site-operator) that can be extensively manipulated:
    + [`site:https://github.com/tillgrallert/digital-muqtabas/blob/master search string`](https://www.google.com/search?q=site%3Ahttps%3A%2F%2Fgithub.com%2Ftillgrallert%2Fdigital-muqtabas%2Fblob%2Fmaster+%D8%B5%D8%AD%D8%A7%D9%81%D8%A9&oq=site%3Ahttps%3A%2F%2Fgithub.com%2Ftillgrallert%2Fdigital-muqtabas%2Fblob%2Fmaster+%D8%B5%D8%AD%D8%A7%D9%81%D8%A9) will search all files in the Digital Muqtabas repository.
    + add [`filetype:xml`](https://www.google.com/search?q=site%3Ahttps%3A%2F%2Fgithub.com%2Ftillgrallert%2Fdigital-muqtabas%2Fblob%2Fmaster+%D8%B5%D8%AD%D8%A7%D9%81%D8%A9+filetype%3Axml&oq=site%3Ahttps%3A%2F%2Fgithub.com%2Ftillgrallert%2Fdigital-muqtabas%2Fblob%2Fmaster+%D8%B5%D8%AD%D8%A7%D9%81%D8%A9+filetype%3Axml) to search only XML files. Other options would be `filetype:md` for plain text markdown files, `filetype.bib` for BibTeX files etc.

    ![Search Google with the `site:` operator](/assets/images/search-google.jpg)

3. a public [Zotero group](https://www.zotero.org/groups/904125/openarabicpe/items) comprising bibliographic metadata for all articles and sections, including author names, titles, publication dates, volume and issue numbers etc., including links to the webview.

    ![Search for *siḥāfa* in the Zoteor group](/assets/images/zotero-group_openarabicpe-search.png)
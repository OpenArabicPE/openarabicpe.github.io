---
layout: page
title: "How to search"
author: Till Grallert
date: 2020-07-08
categories:
- blog
- workflow
tags:
- webview
- search
- how to
---

<script async src="https://cse.google.com/cse.js?cx=012251040084107011117:jof1v_ejndo"></script>

Users will, of course, want to search the edition for specific terms and will immediately recognise the lack of a dedicated search field in the webview. But behold, individual issues can be searched through the built-in search function of your browser. Just hit `ctrl+f` (windows) or `cmd+f` (macintosh) to search individual periodical issues for literal strings. To search across an entire periodical or the whole corpus, there are three instantly available options:

1. Google  provides "[programmable search engines](https://programmablesearchengine.google.com/)", which we have set up to search all of OpenArabicPE's editions by submitting `sitemap.xml` files. Whenever we update our editions, we also re-generate the sitemap and Google will crawl the results. The programmable search engine can be access to the following URL <https://cse.google.com/cse?cx=012251040084107011117:jof1v_ejndo> and integrated into any webpage:
    - <div class="gcse-search"></div>
    - The programmable search engine has the advantage that, if set to Arabic, Google will not only return literal string matches, e.g. a search for *al-ḥurriyya* will also return hits for *ḥurriyya*.
2. Google's web search provides a [`site:` operator](https://moz.com/blog/25-killer-combos-for-googles-site-operator) that can be extensively manipulated:
    + [`site:https://openarabicpe.github.io/ filetype:xml search string`](https://www.google.com/search?q=site%3Ahttps%3A%2F%2Fopenarabicpe.github.io%2F+filetype%3Axml+%D8%A7%D9%84%D9%82%D9%88%D9%8A%D9%85%D8%A9) will search the XML files for all editions hosted via `gh-pages` of repositories belonging to OpenArabicPE.
    + [`site:https://openarabicpe.github.io/journal_al-haqaiq filetype:xml الحرية`](https://www.google.com/search?q=site%3Ahttps%3A%2F%2Fopenarabicpe.github.io%2Fjournal_al-haqaiq+filetype%3Axml+الحرية) will search all XML files of the edition of ʿAbd al-Qādir al-Iskandarānī's *al-Ḥaqāʾiq* for the word *al-ḥurriyya* (liberty).
    + the [`filetype:`] operator is used to limit the scope of the search to a particular file type. Other options would be `filetype:md` for plain text markdown files, `filetype.bib` for BibTeX files etc.

    ![Search Google with the `site:` operator](/assets/images/search-google.jpg)
3. Search the GitHub repository of the periodical you are interested in, such as [*al-Muqtabas*](https://github.com/openarabicpe/journal_al-muqtabas). This allows for browsing and searching and displays search results in context.

    ![Search the GitHub repository](/assets/images/search-github.jpg)

4. The public [Zotero group "OpenArabicPE"](https://www.zotero.org/groups/904125/openarabicpe/items) provides bibliographic metadata for all articles and sections, including author names, titles, publication dates, volume and issue numbers etc. Each reference links to the webview. The Zotero group can therefore be used as a port of entry to our editions.

    ![Search for *siḥāfa* in the Zoteor group](/assets/images/zotero-group_openarabicpe-search.png)
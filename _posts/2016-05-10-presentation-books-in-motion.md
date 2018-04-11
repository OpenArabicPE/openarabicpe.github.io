---
layout: post
title: "Presentation of *Digital Muqtabas* at conference 'Books in Motion' in Beirut"
author: Till Grallert
date: 2016-05-10 23:51:22 +0300
categories:
- blog
- presentation
- project_dh
- project_dape
tags:
- presentation
- conferences
- digital editions
- arabic periodicals
---

I was invited to present *Digital Muqtabas* at the conference "Books in Motion: Exploring concepts of mobility in cross-cultural studies of the book" organised by Sonja Mejcher-Atassi, Hala Auji and James Hodapp (all AUB) that took place at AUB and OIB between 5-7 May 2016. The beautiful conference poster-cum-programme is available as [PDF](http://www.aub.edu.lb/fas/english/Documents/BOOKSinMOTION.pdf).


My paper was titled: "*Majallat al-Muqtabas* between gray online libraries, large-scale scanning efforts, and programming tools: producing fully open, collaborative, and scholarly editions of early Arabic periodicals" and you can find the abstract below. It was part of a panel on digital remediation of the book on Saturday, 7 May, which I shared with David Wrisley (AUB) and Torsten Wollina (OIB). Torsten spoke on the challenges posed by the current state of digitization of books, manuscripts, and catelogues to researchers of the Islamicate world. David presented the fascinating results of course he taught on mapping Beirut's publishing industry. The [abstract to his paper is online](http://djwrisley.com/?p=307) as is the [project website](http://litmap.djwrisley.com/).

As always, I have made the slides available on [GitHub](https://tillgrallert.github.io/Slides/BIM2016).

## Abstract

Moving from the material to the seemingly immaterial, digitisation offers remedies for some of the Middle East's most pressing issues when it comes to books as texts and cultural artifacts: protection, discovery, and access---particularly in times of war and iconoclasm, borders (between territories, linguistic communities, classes etc.), and highly dispersed audiences and artifacts. Yet, digitisation and the infrastructure to deliver digital artifacts is expensive and thus we have not a single scholarly digital edition of early Arabic printed books or periodicals---despite their importance for the history of the *nahḍa*, Arab political nationalism, and the Islamic reform movement; and despite the apparent promises for new methodological approaches to the book.

Some of the largest scanning projects,  [Hathitrust](http://catalog.hathitrust.org/), the [Endangered Archives Programme (EAP)](http://eap.bl.uk/), or [MenaDoc](http://menadoc.bibliothek.uni-halle.de/) produce digital facsimiles for tens of thousands of Arabic books; but facsimiles cannot be searched and reliable OCR of Arabic script is not even available to Google. Gray online-libraries of Arabic literature, namely [*shamela.ws*](http://shamela.ws/), provide access to a vast body of transcriptions of unknown provenance, editorial principals, and quality; but the transcriptions can be neither trusted nor referenced.  

With the [open digital edition of Muḥammad Kurd ʿAlī's *Majallat al-Muqtabas* (1906--18)](https://github.com/tillgrallert/digital-muqtabas 'current state of the project') we want to show that through re-purposing well-established open software and by bridging the gap between immensely popular but non-academic online-libraries of volunteers and academic scanning efforts as well as editorial expertise, one can produce scholarly editions that remedy the short-comings of either world with very small funds: We use [digital texts from *shamela.ws*](http://shamela.ws/index.php/book/26523), transform them into TEI XML---the quasi-standard for digital scholarly editions---add light structural mark-up, bibliographic meta-data, and link each page to facsimiles provided through [EAP](http://eap.bl.uk/database/overview_project.a4d?projID=EAP119;r=63) and [HathiTrust](http://catalog.hathitrust.org/Record/100658549). The digital edition (TEI XML and a basic web display) is then hosted as a public GitHub repository with a [Creative Commons BY-SA 4.0 licence](http://creativecommons.org/licenses/by-sa/4.0/). Improvements  can be crowd-sourced with clear attribution of authorship and version control using  GitHub's core functionality. Editions are referencable down to the word level for scholarly citations, annotation layers, and web-applications through a documented URI scheme. The [web-display](https://rawgit.com/tillgrallert/digital-muqtabas/master/xml/oclc_4770057679-i_60.TEIP5.xml)  can be downloaded and run locally without an internet connection---a necessity for societies outside the global North, which again transforms the book into a highly mobile cultural artifact to be shared among intellectual networks across borders.
---
layout: post
title: "Archive.sakhrit.co's failure as a source for digitsed imagery of Arabic journals"
author: Till Grallert
date: 2016-04-22 23:44:55 +0300
categories:
- blog
tags:
- review
- resources
- online libraries
- digitized resources
---

Recently, a colleague pointed me to yet another gray online library of Arabic material---one that was entirely dedicated to cultural and litrary journals. [Arshīf al-majallāt al-adabiyya wa-l-thaqafiyya al-ʿarabiyya (archive.sakhrit.co)](archive.sakhrit.co) presents a large number of Arabic journals over very long publication periods, providing:

1. Partially watermarked digital imagery
2. Functional tables of content for each issue, including author, title, page number
3. Some bibliographic metadata on the issue level

They do not provide a digital, machine-readable text.

## Focus of the corpus

The focus is on cultural and scientific journals of the 20th century but they also have some journals of the late 19th and early 20th centuries, among them:

- Cairo
    + [al-Muqtaṭaf](http://archive.sakhrit.co/newmagazineYears.aspx?MID=107)
    + [al-Ustādh](http://archive.sakhrit.co/newmagazineYears.aspx?MID=106)
    - [al-Hilāl](http://archive.sakhrit.co/newmagazineYears.aspx?MID=134)
    + [al-Bayān](http://archive.sakhrit.co/newmagazineYears.aspx?MID=161)
    + [al-Manār](http://archive.sakhrit.co/newmagazineYears.aspx?MID=33)
    + [al-Jāmiʿa (al-ʿUthmāniyya)](http://archive.sakhrit.co/newmagazineYears.aspx?MID=114)
    + [al-Zuhūr](http://archive.sakhrit.co/newmagazineYears.aspx?MID=40)
- Lebanon
    - [al-Mashriq](http://archive.sakhrit.co/newmagazineYears.aspx?MID=108)
- Syria
    - [al-Muqtabas](http://archive.sakhrit.co/newmagazineYears.aspx?MID=125)

As one would imagine, I was exited to see a seemingly complete scan of *al-Muqtabas* among the journals hosted by archive.sakhrit. I am currently working on a digital scholarly and collaborative edition of this journal (see the project's [GitHub repository](https://www.github.com/tillgrallert/digital-muqtabas) and [blog](https://tillgrallert.github.io/digital-muqtabas/))[^1] and only found accessible scans of volumes 1 to 8. Thus, the prospect of an additional and potentially complete scan, including volume 9, was exiting. But after my initial enthusiasm, I was in for a serious disappointment.

## Quality of the corpus

As with other gray libraries, such as [al-Maktaba al-Shāmila (shamela.ws)](http://www.shamela.ws), archive.sakhrit is quiet about the personnel or company behind it. It remains unclear where the originals came from, who scanned them, who transcribed the heads, authors, and page numbers seemingly available for every article. The rather illegal / gray nature of the endeavour becomes clear from the shift from a `.com` to a `.co` domain (country code top-level domain for Colombia) documented by the watermark in the imagery that still refers to the `http://Archivebeta.Sakhrit.com` domain.

I have assessed the quality of their "scans" of *al-Muqtabas*. Some volumes/ issues have been scanned from the original or a facsimile edition. Others, such as at least volumes [4](http://archive.sakhrit.co/MagazinePages/Magazine_JPG/AL_moqtabs/Al_moqtabs_1909/Issue_1/001.JPG) and  [5](http://archive.sakhrit.co/MagazinePages/Magazine_JPG/AL_moqtabs/Al_moqtabs_1910/Issue_1/001.JPG), were indeed rendered from a modern digital text, namely shamela's transcription. This is supported by the strikingly similar absence of all footnotes and non-Arabic script; a modern interpunction not present in the original; paragraph breaks that mirror shamela's transcription; and the ellipsis between the two sections of a *bayt*, as provided by shamela (e.g. [archive.sakhrit](http://archive.sakhrit.co/MagazinePages/Magazine_JPG/AL_moqtabs/AL_moqtabs_1910/Issue_7/597.JPG) and [shamela](http://shamela.ws/browse.php/book-26523#page-3548)). The final evidence to prove this argument is that an uncommented gap of almost three pages in shamela's transcription of volume 5(7) is reproduced in archive.sakhrit's supposed facsimiles (compare the issue on [digital-muqtabas](https://tillgrallert.github.io/digital-muqtabas/xml/oclc_4770057679-i_54.TEIP5.xml#pb_61.d1e2036), [shamela](http://shamela.ws/browse.php/book-26523#page-3554), and [archive.sakhrit](http://archive.sakhrit.co/MagazinePages/Magazine_JPG/AL_moqtabs/AL_moqtabs_1910/Issue_7/605.JPG)).

{% include image.html url="http://archive.sakhrit.co/MagazinePages/Magazine_JPG/AL_moqtabs/AL_moqtabs_1910/Issue_7/605.JPG" description="At archive.sakhrit and shamela the text stops at من هذا الناشيء" class=""  %}

{% include image.html url="http://eap.bl.uk/EAPDigitalItems/EAP119/EAP119_1_4_4-EAP119_muq191008_463_L.jpg" description="Scans of the original page reveal that the text just continues on line 6 with ابو ابعباس" class=""  %}

Another, rather common, problem is archive.sakhrit's bibliographic metadata on both the article and the issue level. The first is obviously poised by the reference to image renderings of shamela's transcription, whose pagination does not correspond to the printed original. In addition, the tables of content provide only an eclectic selection of articles and sections and many articles are mis-attributed (for an example compare [the MODS file for out digital edition of Muqtabas 4(1)](https://tillgrallert.github.io/digital-muqtabas/metadata/oclc_4770057679-i_37.MODS.xml) with [archive.sakhrit's *fihris* of the same issue](http://archive.sakhrit.co/contents.aspx?CID=5685)).
The second issue relates to the publication dates. For *al-Muqtabas*, archive.sakhrit assumes a publication schedule in which volumes correspond to Gregorian years and issues correspond to Gregorian months (i.e. according to archive.sakhrit Muqtabas 1(1) was published on [1 January 1906](http://archive.sakhrit.co/contents.aspx?CID=5649)). This is despite the fact that *al-Muqtabas* clearly states its publication schedule on the front page of every volume as adhering to the *hijrī* calendar for both volumes and issues (e.g. [archive.sakhrit's facsimile of this issue's first page](http://archive.sakhrit.co/MagazinePages/Magazine_JPG/AL_moqtabs/AL_moqtabs_1906/Issue_1/001.JPG). As a consequence, bibliographic data obtained from archive.sakhrit cannot be considered reliable in any sense.

Therefore archive.sakhrit is even more problematic than shamela in terms of scholarly use. The user is always aware of reading a derivative with an unknown relation to an assumed original while accessing a text from shamela. At archive.sakhrit, on the other hand, the user is deceived by a seemingly faithful representation of a fake original.


## Access, structure of the website

In addition to the user interface of the website, which has a severe 1990s look and feel but otherwise seems to be fully functional, the collection can be accessed in a number of ways that would ease automated access for other applications.

+ Individual issues can be accessed
    * by modifying the php call: `http://archive.sakhrit.co/newPreview.aspx?ISSUEID=5649`
    * note that `ISSUEID` is a single variable across the entire website and not specific to any one single journal.
    * note also that issues of an individual journal have no consecutive `ISSUEID`s.
 + individual page images can be accessed through a seemingly structured URL:
     * `http://archive.sakhrit.co/MagazinePages/Magazine_JPG/AL_moqtabs/AL_moqtabs_1906/Issue_1/001.JPG`
     * `http://archive.sakhrit.co/MagazinePages/Magazine_JPG/AL_moqtabs/AL_moqtabs_1906/Issue_11/553.JPG`

[^1]: I have cross-posted this post to the *Digital Muqtabas*' project [blog](https://tillgrallert.github.io/blog/2016/04/22/review-archive-sakhrit/).
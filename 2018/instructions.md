---
layout: default
title: Paper Submission Instructions
excerpt: "Paper Submission Instructions for Expressive 2018"
headline: "Paper Submission Instructions"
year: 2018
---

All work must be previously unpublished. Production and Meta papers need not contain original research or results, but must make a substantive contribution to the knowledge in the field. Papers should be 8–10 pages in length (excluding citations). Papers longer than 10 pages must make a very significant contribution. Supplemental video and images may also be submitted. Papers are reviewed double-blind and so must be anonymous when submitted. References to your own work should be made in the third person to maintain anonymity.

Paper submission is electronic using the [EasyChair system]({{site.symposium.submission}}).

### Paper formatting

Manuscripts must be written in English. They should follow the [ACM SIGGRAPH publication guidelines](http://www.siggraph.org/learn/instructions-authors), including a title page with an abstract, keywords, and a bibliography. For formatting, please use the [ACM Master Article Template](https://www.acm.org/publications/proceedings-template) with the _sigconf_ style.

* LaTeX (Version 1.49) [template](https://www.acm.org/binaries/content/assets/publications/consolidated-tex-template/acmart-master.zip).
* Microsoft Word [template for Windows](https://portalparts.acm.org/hippo/acm_windows_word_template.zip).
* Microsoft Word [template for Mac 2016](https://portalparts.acm.org/hippo/acm_mac_2016_word_template.zip).

The use of LaTeX is encouraged and preferred. However, only PDF files will be accepted for your submission. Please make sure that all fonts are embedded.

#### Setting up the LaTex template

To setup the LaTeX template for anonymous submission, assign the _sigconf_ style in the document class as follows:

```
\documentclass[sigconf,review,anonymous]{acmart}
```

For the camera-ready submission, please remove the `review` and `anonymous` configuration of the document class.

Additionally, please set the conference details in the template as follows:

```
%Conference
\acmConference[EXPRESSIVE 2018]{EXPRESSIVE 2018}{August 17--19, 2018}{Victoria, British Columbia, Canada}
\acmYear{2018}
\copyrightyear{2018}
\setcopyright{none}
```

For the camera-ready submission, please remove `\setcopyright{none}`. To comply with the ACM copyright policies.

### Supplemental material
{: .top1}

Supplemental material such as additional images or videos may be submitted as PDF or as a zipped archive (ZIP files) with a maximum size of 30 MB.

#### Video Formatting

Videos should be a maximum of 5 minutes in length and contain either clearly spoken English audio or subtitles. Please ensure that a commonly available format and codec is used. Suggested video specifications are: MP4 container format, with H.264 video encoding and AAC audio encoding. Videos can be converted into this format using freely available tools, such as [Handbrake](https://handbrake.fr/). Make sure that the video plays with [VLC](https://www.videolan.org/vlc/), which is available on most platforms.

---

## General Submissions
{: .top2}

Posters, demos, and artworks should be submitted in PDF format as an extended abstract (2 or more pages). They should follow the ACM SIGGRAPH publication guidelines described above. Rejected papers may be considered for the poster track.

---

## Proceedings
{: .top2}

Accepted papers and general submissions (posters/demos/artworks) will be published as a single conference proceedings by the ACM and will be available online via the [ACM Digital Library](http://dl.acm.org/). Papers will also be archived in the [Eurographics Digital Library](https://diglib.eg.org/).

> Authors of selected papers will be invited to submit extended versions of their manuscripts to be considered for publication in a special section of [Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics/) journal (Elsevier) via a fast-track review process.

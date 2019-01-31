---
layout: submission
title: ACM/EG Expressive 2019 — Call for Submissions
excerpt: "Submit your work to Expressive 2019"
image:
  card: 2019/expressiveCard.jpg
year: 2019
---

The Expressive symposium explores the capacity of computer graphics, animation, and computational media to be used in artistic, aesthetic, and creative ways. The field can be seen as encompassing problems in expressive __understanding__, expressive __communication__, and expressive __interaction__:

* Expressive __understanding__ integrates aspects of computer science, philosophy, psychology, and the fine, applied, and performing arts, investigating theoretical approaches that further our understanding of aesthetic evaluation, perception and meaning.

* Expressive __communication__ focuses on imagery and motion which is expressive rather than photorealistic, although it may incorporate realistic elements.

* Expressive __interaction__ explores models, algorithms, and technologies for sketch-based interfaces, particularly classifying and recognizing hand-drawn shapes as a way to create or edit digital models, text, mathematics, or 3D shapes.

[Expressive 2019](http://expressive.graphics/2019) will take place in Genova, Italy, May 5-6, 2019 --- co-located with [Eurographics 2019](https://www.eurographics2019.it/) in Genova.

Expressive technical papers will be submitted, evaluated, and presented in a single, unified track. This unification reflects the ongoing evolution of the symposium, which originated as the union of three separate events: Computational Aesthetics (CAe), Non-Photorealistic Animation and Rendering (NPAR), and Sketch-Based Interfaces and Modelling (SBIM). The symposium will also include an arts program, posters and demos, and presentations of published journal articles.

{::options parse_block_html="true" /}
<a href="#call-for-papers" class="bold"> > Call for Papers</a><br>
<a href="#call-for-posters-and-demos" class="bold"> > Call for Posters and Demos</a><br>
<a href="#call-for-artworks--generative-chronicles" class="bold"> > Call for Artworks</a><br>
<a href="#call-for-journal-presentations" class="bold"> > Call for Journal Presentations</a>
{::options parse_block_html="false" /}

---

## Call for Papers
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for Papers (PDF)](/docs/expressive-2019-call-for-papers-v04.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture abstractduetime %}{{site.symposium[page.year].abstract | date: '%s'}}{% endcapture %}
{% capture paperduetime %}{{site.symposium[page.year].paper | date: '%s'}}{% endcapture %}
{% capture extensionduetime %}{{site.symposium[page.year].extension | date: '%s'}}{% endcapture %}
{% capture acceptanceduetime %}{{site.symposium[page.year].acceptance | date: '%s'}}{% endcapture %}
{% capture camerareadyduetime %}{{site.symposium[page.year].camera-ready | date: '%s'}}{% endcapture %}

{% if site.symposium[page.year] contains 'abstract' %}| __Abstract due:__ {% if abstractduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].abstract }}{% if abstractduetime < nowtime %}~~{% endif %} |{% endif %}
| __Paper submission deadline:__ {% if paperduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].paper }}{% if paperduetime < nowtime %}~~{% endif %} |
{% if site.symposium[page.year] contains 'extension' %}| __Extended deadline:__ {% if extensionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].extension }}{% if extensionduetime < nowtime %}~~{% endif %} |{% endif %}
| __Acceptance notification:__ {% if acceptanceduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].acceptance }}{% if acceptanceduetime < nowtime %}~~{% endif %} |
{% if site.symposium[page.year] contains 'camera-ready' %}| __Camera-ready submission:__ {% if camerareadyduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].camera-ready }}{% if camerareadyduetime < nowtime %}~~{% endif %} |{% endif %}
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

### Submission Types
{: .top1}

Paper submissions are invited across the broad range of areas covered by Expressive. We welcome papers in several categories:

* __Research:__ New algorithms, scientific studies, analysis, or data (i.e., traditional academic papers). Research papers must contain novel results that make a substantive contribution to the field.
* __Production:__ Candid discussion of the process of creating a work (e.g., film, image, game) or developing a tool (e.g., paint or CAD program, software library). We are equally interested in papers on the use of existing techniques combined in novel ways, or their application in a new or unusual context.
* __Creative:__ Descriptions of original creative projects or analyses of expressive techniques used in artworks, performances, or computational design projects. Creative papers should highlight artistic innovation, and we encourage artists submitting to the Expressive 2019 Art Exhibition to also submit a creative paper describing their project.

* __Meta:__ Statements about research that do not contain new results, e.g.: grand challenges, position papers, evaluation standards, surveys, and primers on art / aesthetics / psychophysics for a computer science audience. We welcome papers that discuss the challenges of bridging computational expression across disciplines.

Submissions can also overlap more than one of these categories. Accepted papers will be published as a single conference proceedings by the ACM and will be available online via the [ACM Digital Library](http://dl.acm.org/). Papers will also be archived in the [Eurographics Digital Library](https://diglib.eg.org/).


**Authors of selected papers will be invited to submit extended versions of their manuscripts to be considered for publication in a special section of [Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics/) journal (Elsevier) via a fast-track review process.**

### Submission Topics
{: .top1}

Topics include, but are not limited to:

* Analysis and modeling of creative behavior (AI, A-life)
* Simulation of natural media, traditional styles, and novel artistic styles
* Analysis of image style and saliency (paintings, photographs, others)
* Visualization techniques
* Simplification and abstraction techniques (e.g. sketching, indication)
* Empirically-based metrics of aesthetic attributes
* Applied visual perception
* Interaction techniques (e.g. sketch, gestural, multi-touch, multi-modal)
* Sketch-parsing, classification and recognition
* Novel interfaces for art creation, modeling, control, sketch input, etc.
* Study designs and methodologies for evaluating and validating sketch-based systems, aesthetic metrics, visual communication systems, etc.
* Advanced rendering techniques (e.g. volumetric, GPU, mobile, multi-modal)
* Applications in special domains: Medicine, Geology, Biology, Sociology, etc.
* Sketch-based information retrieval
* Stylistic or aesthetic aspects of character animation and simulated physics
* Accounts of real productions (e.g., animated films, digital art) or applications in software products (e.g., modeling, visualization, presentation software)
* Visual composition
* Design, rendering, and evaluation of layouts for text and presentation graphics
* Example-based style transfer
* Deep learning and neural networks for expressive rendering (e.g. neural style transfer)
* Temporal and spatial coherence
* Aesthetic evaluation and stylistic rendering of visual effects such as motion blur, depth of field, and lighting
* Non-traditional camera models


### Submission Information
{: .top1}

All work must be previously unpublished. Production and Meta papers need not contain original research or results, but must make a substantive contribution to the knowledge in the field. Papers should be 4–10 pages in length (excluding citations). Papers longer than 10 pages must make a very significant contribution. 

Paper submission is electronic using the [SRM]({{site.symposium[2019].submission}}) system. Expressive uses a double-blind reviewing process, so submissions should be appropriately anonymized.
For detailed instructions to submit papers, posters, videos and other materials, please view the [submission instructions](http://expressive.graphics/2019/instructions/).

---

## Call for Posters and Demos
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for Posters and Demos (PDF)](/docs/expressive-2019-call-for-posters-demos-v02.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture generalposterdemosubmissionduetime %}{{site.symposium[page.year].general-poster-demo-submission | date: '%s'}}{% endcapture %}

| __Poster/Demos submission deadline:__ Rolling notification, closes {% if generalposterdemosubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].general-poster-demo-submission }}{% if generalposterdemosubmissionduetime < nowtime %}~~{% endif %} |
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

Expressive 2019 will host an exhibition for artworks (see [Call for Artworks](#call-for-artworks--generative-chronicles)), posters and demonstration projects, where artistic pieces, computational demonstrations, and posters, will be featured side-by-side. In this category, we focus on recent research and creative activities at the intersection of arts and sciences. We are open to any work and research that is related to topics of the Expressive 2019 conference. The authors of accepted works will be invited to present their work through a panel discussion or short oral presentation within the main Expressive 2019 conference. Accepted works will be archived through the [ACM Digital Library](http://dl.acm.org/) and [Eurographics Digital Library](https://diglib.eg.org/).

### Topics

We seek submissions for posters and demos. We are interested in a wide variety of works that bridge arts and sciences. We are particularly interested in techniques for visually communicating ideas and information and for sketch based interaction and modeling integration through integration of computer science, mathematics, philosophy, psychology, and the fine, applied & performing arts.

Expressive solicits extended abstracts for posters and demos. Accepted works will be demonstrated and displayed during the conference. We expect these works will pose new questions and motivate further research in the main areas of Expressive: understanding, communication, and interaction.

Accepted submissions for Posters and Demos will be published together with the accepted papers as a single conference proceedings by the ACM and will be available online via the [ACM Digital Library](http://dl.acm.org/). Accepted submissions will also be archived in the [Eurographics Digital Library](https://diglib.eg.org/).

### Guidelines

We seek posters and demos submissions that show work that pertains to all topics of Expressive 2019. All submissions should be in the form of an extended abstract of 1 to 2 pages, written in English, including a title page with an abstract, keywords, and a bibliography. Submissions should provide a clear description of the work and the process. Posters and demos will be demonstrated and/or displayed at the conference venue. Authors of accepted works in all areas of submitted work are encouraged to bring a demonstration of their work as well; it is not necessary to create a separate submission for a poster and a demo if they refer to the same project.

### Submission

All submissions must be made through the Eurographics SRM conference submission site. Please feel welcome to contact the Posters and Demos chair Jose Echevarria at [{{site.symposium[page.year].contact-poster-demo}}](mailto:{{site.symposium[page.year].contact-poster-demo}}) if you have any questions.

For detailed instructions to submit posters, demos and other materials, please view the [submission instructions](http://expressive.graphics/2019/instructions/).

---

## Call for Artworks — _Generative Chronicles_
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for Artworks (PDF)](/docs/expressive-2019-call-for-artworks-v04.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture generalartworksubmissionduetime %}{{site.symposium[page.year].general-artwork-submission | date: '%s'}}{% endcapture %}

| __Artwork submission deadline:__ Rolling notification, closes {% if generalartworksubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].general-artwork-submission }}{% if generalartworksubmissionduetime < nowtime %}~~{% endif %} |
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

### Theme: _Generative Chronicles_

What are the possible transformations and processes underlying the genesis of a visual form? For the Expressive 2019 Arts Program, we invite artwork submissions that explore, visualize, challenge, or reflect upon the process embedded in the artwork itself. This includes, but is not limited to:

* Simulations and visualizations of biologically inspired growth/decay processes;
* Procedurally-generated graphics and expressive animations that highlight the steps required for their generation;
* Digital elaborations upon the cognitive and motor processes underlying the act of human art making (e.g. painting/drawing/sculpting);
* Rule-based design systems that generate a myriad of visual outcomes;
* Multimodal visualizations exploring the art-making process;
* Projects that utilize glitches or explore serendipity.

Projects may take the form of computer animations and interactive installations, 
but we also welcome prints, digitally fabricated objects, as well as handmade drawings or design notes. 

For each submission, we require an extended abstract of 2 to 4 pages. The extended abstract should describe, illustrate, and discuss how the work relates to the theme of **Generative Chronicles** or to the Expressive Symposium's focus on expressive understanding, expressive communication, and expressive interaction. We suggest the inclusion of at least one representative image in the extended abstract.

Submissions can also optionally include supplementary materials, such as additional images, links to a video or website, and technical and installation requirements. Extended abstracts will be published in the ACM/EG Expressive 2019 conference proceedings, and archived through the [ACM Digital Library](http://dl.acm.org/) and [Eurographics Digital Library](https://diglib.eg.org/). **We also encourage dual submissions to the Arts Program and the main Expressive papers track**. The authors of accepted works will be invited to present their work through a panel discussion or short oral presentation within the main Expressive 2019 conference. All submissions must be made through the Eurographics SRM conference submission site.

**Authors of selected papers will be invited to submit extended versions of their manuscripts to be considered for publication in a special section of [Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics/) journal (Elsevier) via a fast-track review process.**

Please feel welcome to contact the Arts Program chairs Pedro Cruz and Daniel Berio at [{{site.symposium[page.year].contact-arts}}](mailto:{{site.symposium[page.year].contact-arts}}) if you have any questions.

For detailed instructions to submit artworks and other materials, please view the [submission instructions](http://expressive.graphics/2019/instructions/).

---

## Call for Journal Presentations
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for Journal Presentations (PDF)](/docs/expressive-2019-call-for-journal-presentations-v03.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture journalsubmissionduetime %}{{site.symposium[page.year].journal-submission | date: '%s'}}{% endcapture %}

| __Presentation of work previously published in a journal:__ Rolling notification, closes {% if journalsubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].journal-submission }}{% if journalsubmissionduetime < nowtime %}~~{% endif %} |
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

As at previous events, we will include a submission category for the presentation of work previously published in a journal (e.g. TVCG, C&G, CGF, TOG). The intent of this category is to allow authors of journal papers the opportunity to present their research at Expressive. These papers will not appear in the Expressive proceedings.

### Guidelines

The work should be published in the July 2018 -- July 2019 time-frame, and not have been previously presented at a conference or symposium. A copy of the paper abstract and a link to the published paper or preprint should be submitted via email to the program chairs. Submissions will be reviewed by the program committee. Note that accepted presentations are subject to the same rules as regular papers, namely that at least one author must register for the conference.

---

### Contact

Conference chairs can be contacted via the following emails:

* General chairs: [{{site.symposium[page.year].contact}}](mailto:{{site.symposium[page.year].contact}})
* Program/Paper chairs: [{{site.symposium[page.year].contact-papers}}](mailto:{{site.symposium[page.year].contact-papers}})
* Arts chairs: [{{site.symposium[page.year].contact-arts}}](mailto:{{site.symposium[page.year].contact-arts}})
* Poster + Demo chair: [{{site.symposium[page.year].contact-poster-demo}}](mailto:{{site.symposium[page.year].contact-poster-demo}})

{::options parse_block_html="true" /}

<div class="panel panel-default">

#### Conference Chairs
{: .panel-heading .top2}
<div class="panel-body">

| __General Co-chairs:__ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|| {{ site.chairs2019.general }}, _{{ site.chairs2019.generalAff }}_
|                        || {{ site.chairs2019.general2 }}, _{{ site.chairs2019.general2Aff }}_
|                        || {{ site.chairs2019.general3 }}, _{{ site.chairs2019.general3Aff }}_
| __Program Co-chairs:__ || {{ site.chairs2019.program }}, _{{ site.chairs2019.programAff }}_
|                            || {{ site.chairs2019.program2 }}, _{{ site.chairs2019.program2Aff }}_
|                            || {{ site.chairs2019.program3 }}, _{{ site.chairs2019.program3Aff }}_
| __Arts Program Co-chairs:__ || {{ site.chairs2019.art }}, _{{ site.chairs2019.artAff }}_
|                                 || {{ site.chairs2019.art2 }}, _{{ site.chairs2019.art2Aff }}_
| __Posters and Demo Chair:__ || {{ site.chairs2019.postersdemo }}, _{{ site.chairs2019.postersdemoAff }}_
| __Publicity Chair:__      || {{ site.chairs2019.publicity }}, _{{ site.chairs2019.publicityAff }}_

</div>
</div>

{::options parse_block_html="false" /}

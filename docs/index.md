---
layout: default
speakers:
  - name: Corrie Painter
    inst: Count Me In and Broad Institute
    url: https://www.broadinstitute.org/bios/corrie-painter
    blurb: "Corrie Painter is the Associate Director of Count Me In and is a research scientist at the Broad Institute of MIT and Harvard.  A trained cancer researcher with a Ph.D. in biochemistry, she completed her postdoctoral work in cancer immunology, focused on melanoma. In 2010, Painter was diagnosed with angiosarcoma. She has combined her cancer advocacy and scientific background to engage with patients in order to build and carry out patient-partnered genomics studies. She is also the co-founder of Angiosarcoma Awareness Inc."
  - name: Rafael Irizarry
    inst: Harvard University
    url: https://rafalab.github.io
    blurb: "Rafael Irizarry is Professor and Chair of the Department of Data Sciences at the Dana-Farber Cancer Institute and a Professor of Biostatistics at Harvard School of Public Health, and one of the original founders of the Bioconductor Project. Professor Irizarry’s work has focused on problems related to microarray, next-generation sequencing, and genomic data. Currently, he is interested in leveraging his knowledge in translational work, e.g. developing diagnostic tools and discovering biomarkers. During his career, he has co-authored papers on a variety of topics including musical sound signals, infectious diseases, circadian patterns in health, fetal health monitoring, and estimating the effects of Hurricane María in Puerto Rico."
  - name: Caroline Uhler
    inst: ETH Zurich, Switzerland
    url: https://www.carolineuhler.com
    blurb: "Caroline Uhler, formerly Associate Professor at MIT in Cambridge, USA, recently joined the ETH Zurich, Switzerland, as Professor of Machine Learning, Statistics and Genomics. Her research focuses on statistics, machine learning and computational biology. In particular, graphical models, causal inference, algebraic statistics and applications to genomics, for example linking the spatial organization of the DNA with gene regulation."
  - name: Kylie Ariel Bemis
    inst: Northeastern University
    url: https://kuwisdelu.github.io
    blurb: "Kylie Bemis is a faculty in the Khoury College of Computer Sciences at Northeastern University where she teaches data science and develops curriculum for the MS in Data Science program. Her research interests include machine learning and large-scale statistical computing for bioinformatics. She is active in outreach to the Native American and LGBTQ communities, an enrolled member of the Zuni tribe, and a writer of fiction and poetry."
  - name: Fei Chen
    inst: Broad Institute
    url: https://www.insitubiology.org
    blurb: "Fei Chen is currently a Fellow at the Broad Institute. During the course of his doctoral studies in Biological Engineering at MIT, Fei co-invented expansion microscopy (ExM): A breakthrough technique that allows for super-resolution imaging of biological samples with conventional light microscopes. Chen's lab utilizes ExM as a platform for in situ transcriptomics and epigenomics, while continuing to pioneer novel molecular and microscopy tools to uniquely illuminate biological pathways and function."
  - name: Aaron Lun
    inst: Genentech
    url: https://ltla.github.io/about
    blurb: "Aaron Lun is a Scientist at Genentech, and previously was a research associate in John Marioni’s group at the CRUK Cambridge Institute and completed a PhD with Gordon Smyth at the Walter and Eliza Hall Institute for Medical Research in Melbourne. Aaron is a prolific contributor to the Bioconductor project, currently especially in the area of single-cell RNA-seq."
  - name: Xiaole Shirley Liu
    inst: Harvard University
    url: https://liulab-dfci.github.io
    blurb: "Shirley Liu is a Professor with the Department of Biostatistics and Computational Biology at the Dana-Farber Cancer Institute and Harvard School of Public Health. Her research focuses on algorithm development and integrative mining from big data generated on microarrays, massively parallel sequencing, and other high throughput techniques to model the specificity and function of transcription factors, chromatin regulators and lncRNAs in tumor development, progression, drug response and resistance."
---

{% include header.md %}

**COVID-19 update**: (May 28, 2020) Due to COVID-19 restrictions on gathering and travel, the organizing committee has decided to shift this year’s conference to a virtual platform. [Register](https://datasciences.eventsmart.com/events/bioc2020/).

BioC2020 highlights current developments within and beyond
the [Bioconductor](https://www.bioconductor.org) project. The structure of the conference is still being determined but will contain the following:

* live-streamed keynotes with live Q&A sessions
* recorded contributed talks with live Q&A sessions
* interactive workshops
* virtual poster session

NEW: [Registration for virtual Bioc2020 is now open](https://datasciences.eventsmart.com/events/bioc2020/)
A new flat-rate fee of $50.00 USD will give attendees access to the virtual platform for the conference and access to live streamed talks and Q&As. The new [registration](https://datasciences.eventsmart.com/events/bioc2020/) deadline is July 20, 2020.

The organizing committee is working on a conference schedule that will address the many time zones that people will be participating from. More information will be forthcoming.  The meeting will occur over 5 days, July 27-31.

Conference flyer [#1](images/flyers/BioC2020Flyerlandscape_lg.pdf), [#2](images/flyers/BioC2020FlyerPortrait.pdf)

**New!** Nominate individuals providing outstanding contributions to the Bioconductor project and community to the [Bioconductor Awards 2020](https://tinyurl.com/biocawards2020). Deadline for nominations: June 15. 

## Key dates for virtual Bioc2020
<!--
- Jan 9: Registration Opens
- Jan 15: [Call for abstracts/applications for talks, early posters, travel and caregiver awards, workshops](call-for-abstracts.html)
- March 3: Deadline for proposals for talks, workshops, early posters
- March 15: Call for [travel](./scholarships.md) and [caregiver](./caregiver-awards.md) awards
- March 24: Notification of decision for talks, workshops, early posters
- June 15: Deadline for nominations to the [Bioconductor Awards 2020](https://tinyurl.com/biocawards2020)
- June 30: Deadline for travel and caregiver awards
- July 1: Deadline for late posters and for __Birds of a Feather__ meetings
- July 6: Notification of decision for travel and caregiver awards
- July 10: Notification of decision for late posters
- July 10: Last day of early registration
- July 27-31: BioC2020 Meeting

-->

The call for abstracts/applications for talks, early posters is closed.
Call for scholarships remains open and will waive the virtual registration fee.  


- June 1:  [Registration](https://datasciences.eventsmart.com/events/bioc2020/) Opens for virtual Bioc2020
- June 15: Deadline for nominations to the [Bioconductor Awards 2020](https://tinyurl.com/biocawards2020)
- June 30: Deadline for [scholarships](./scholarships.md) and [caregiver](./caregiver-awards.md) awards
- July 1:  Deadline for late posters and for __Birds of a Feather__ meetings
- July 6:  Notification of decision for scholarships and caregiver awards
- July 10: Notification of decision for late posters
- July 10: Last day of early registration
- July 27-31: BioC2020 Meeting

## Confirmed Speakers

{% for s in page.speakers %}
{% assign imgpath = "images/speakers/" | append: s.name | remove: ' ' | append: '.jpg' %}
<img src="{{ imgpath }}" style="float:right; width:120px; height:150px; object-fit: cover">
### [{{ s.name }}]({{ s.url }}), {{ s.inst }}

> {{ s.blurb }}

{% endfor %}

More information: [workshop@bioconductor.org][contact]

<a href="https://twitter.com/intent/tweet?button_hashtag=bioc2020&ref_src=twsrc%5Etfw"
    class="twitter-hashtag-button"
    data-show-count="false">Tweet #bioc2020</a>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[contact]: mailto:workshop@bioconductor.org?subject=BioC2020%20question
[survey]: https://forms.gle/eRWv3tdXLvxYT2CYA

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: PhosR
summary: PhosR enables processing and functional analysis of phosphoproteomic data
authors: []
tags: 
- Multi-omics
categories: []
date: 2020-10-23T19:20:54+11:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: PhosR_schematic
  focal_point: Smart
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Manuscript
  url: https://www.biorxiv.org/content/10.1101/2020.08.31.276329v1
  icon_pack: far
  icon: newspaper
- name: Github
  url: https://github.com/PYangLab/PhosR
  icon_pack: fab
  icon: github

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Mass spectrometry (MS)-based phosphoproteomics has revolutionised our ability to profile phosphorylation-based signalling in cells and tissues on a global scale. To infer the action of kinases and signalling pathways in phosphoproteomic experiments, we present PhosR, a set of tools and methodologies implemented in a suite of R packages facilitating comprehensive analysis of phosphoproteomic data. By applying PhosR to both published and new phosphoproteomic datasets, we demonstrate capabilities in data imputation and normalisation using a novel set of ‘stably phosphorylated sites’,and in functional analysis for inferring active kinases and signalling pathways. In particular, we introduce a ‘signalome’ construction method for identifying a collection of signalling modules to summarise and visualise the interaction of kinases and their collective actions on signal transduction. Together, our data and findings demonstrate the utility of PhosR in processing and generating novel biological knowledge from MS-based phosphoproteomic data.

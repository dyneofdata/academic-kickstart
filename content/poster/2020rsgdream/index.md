---
title: "Detecting higher-order structural changes in 3D genome organization with multi-task matrix factorization"
poster: true
event: Research in Computational Molecular Biology (RECOMB) / Regulatory and Systems Genomics with DREAM Challenges (RSGDREAM)
event_url: https://www.iscb.org/recomb-regsysgen2020
location: Virtual/online
summary: ""
abstract: "Three-dimensional (3D) genome organization, which determines how the DNA is packaged inside the nucleus, has emerged as a key regulatory mechanism of cellular processes. High-throughput chromosomal conformation capture (Hi-C) technologies have enabled the study of 3D genome organization by experimentally measuring interactions among genomic regions in 3D space. Analysis of Hi-C data has revealed higher-order organizational units at multiple resolutions: chromosomal territories, compartments, and topologically associating domains (TADs). Changes or disruptions to such structures have been associated with disease, developmental, and evolutionary processes. Therefore, a key problem is to systematically detect higher-order structural changes across Hi-C datasets from multiple conditions. Existing methods to detect changes in 3D genome organization either do not model higher-order structural units, are specialized to one type of unit (e.g., TADs), or only compare pairs of Hi-C datasets. We address these limitations with Tree-structured Graph-regularized Integrated Factorization (TGIF), a new multi-task Non-negative Matrix Factorization (NMF) approach. TGIF makes use of complex tree-structured relationships among multiple Hi-C datasets such that closely related tasks, one for each Hi-C matrix, have similar lower-dimensional factors. The factors can be further constrained with task-specific graph regularization and are used to extract clusters of genomic regions with dynamically changing interaction profiles across tasks. We applied TGIF to simulated data and in real Hi-C data from cancer cell lines and mouse neural development process. TGIF effectively recovers ground-truth clusters in simulated data even with a large amount of noise and sparsity. When applied to genome-wide Hi-C matrices from karyotypically normal hematopoietic stem and progenitor cells (HSPC) and two chronic myelogenous leukemia (CML) cell lines (K562 and KBM7), TGIF detects the Philadelphia translocation, a large reciprocal translocation between chr9 and chr22 used in the diagnosis of CML. In per-chromosome Hi-C matrices from three cell states during mouse neural development (embryonic stem cell, neural progenitors, and cortical neurons), TGIF is able to identify compartmental switches as well as local TAD shifts accompanying change in nearby gene expression. Taken together, TGIF provides a powerful multi-task framework to study the dynamics and context-specificity of 3D genome organization."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-11-16T13:00:00"
date_end: "2020-11-19T15:00:00"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: ["Da-Inn Lee", "Sushmita Roy"]
tags: ["Dimension Reduction", "3D Genome"]

# Is this a featured talk? (true/false)
featured: falses

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
#- icon: image
#  icon_pack: fas
#  name: Poster
#  url: https://drive.google.com/file/d/1lBRGjPY4rCSwUWBuWhuLFvo_E0VanfRu/view?usp=sharing 
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#- internal-project

# Enable math on this page?
math: true
---


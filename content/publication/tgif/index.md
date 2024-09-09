---
title: "Examining dynamics of three-dimensional genome organization with multi-task matrix factorization"
authors:
- Da-Inn Lee
- Sushmita Roy
date: "2023-08-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "biorxiv"
publication_short: ""

abstract: Three-dimensional (3D) genome organization, which determines how the DNA is packaged inside the nucleus, has emerged as a key component of the gene regulation machinery. The availability of high-throughput chromosome conformation datasets, such as Hi-C, across multiple conditions and time points offer a unique opportunity to examine changes in 3D genome organization and link them to phenotypic changes in normal and diseases processes. However, systematic detection of higher-order structural changes across multiple Hi-C datasets is a major challenge. Existing computational methods either do not model higher-order structural units or cannot model dynamics across more than two conditions of interest. We address these limitations with Tree-Guided Integrated Factorization (TGIF), a generalizable multi-task Non-negative Matrix Factorization (NMF) approach that can applied to time series or hierarchically related biological conditions. TGIF can identify large-scale compartmental changes as well as smaller topologically associated domain-level changes. Compared to existing methods, TGIF identifies has fewer false positive TAD boundary changes. Application to two mammalian developmental time courses provides multi-scale characterization of genome dynamics that we validate with enrichment of one-dimensional regulatory signals from histone modifications, accessibility and architectural proteins. Finally, we leverage TGIF boundaries to prioritize sequence variants for multiple phenotypes from the NHGRI GWAS catalog. Taken together, TGIF is a flexible tool to examine 3D genome organization dynamics across disease and developmental processes. 

# Summary. An optional shortened abstract.
summary: Tree-Guided Integrated Factorization (TGIF) is a pipeline designed to simultaneously analyze multiple input Hi-C datasets representing related biological conditions and identify conserved or context-specific structural elements that build up the 3D genome. 

tags:
- 3D Genome
- Dimension Reduction
- Multi-task Learning

featured: true

links:
- name: Full
  url: https://doi.org/10.1101/2023.08.25.554883 

url_pdf: https://www.biorxiv.org/content/10.1101/2023.08.25.554883v2.full.pdf 
url_code: https://github.com/Roy-lab/tgif
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Overview of [**TGIF**](https://github.com/Roy-lab/tgif)'
  focal_point: "center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
 

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Linking dynamics of 3D genome organization to cardiac development & disease"
event: National Library of Medicine (NLM) Informatics Training Conference 
event_url: 
location: Stanford, CA
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Three-dimensional (3D) genome organization, which determines how the DNA is packaged inside the nucleus, has emerged as a key regulatory mechanism of cellular processes. High-throughput chromosomal conformation capture (Hi-C) technologies have enabled the study of 3D genome organization by experimentally measuring interactions among genomic regions in 3D space. Changes in 3D genome organization have been associated with gene expression changes during cell fate-specification as well as with diseases such as cancer. Therefore, a key challenge in regulatory genomics is to systematically detect higher-order structural changes across Hi-C datasets from multiple conditions. Existing computational methods either do not model higher-order structural units or do not take into account complex relationships among the conditions of interest. We address these limitations with Tree-Guided Integrated Factorization (TGIF), a new multi-task Non-negative Matrix Factorization (NMF) approach. TGIF models arbitrary relationships among multiple Hi-C datasets as a tree such that closely related Hi-C datasets have similar lower-dimensional representation. TGIF provides a statistically significant set of differential TAD boundaries with higher precision than existing approaches. When applied to cardiomyocyte differentiation time-course data, TGIF identifies known and novel boundary elements specific to each stage of development. We also find that cardiovascular-disease-associated SNPs are depleted in TGIF boundaries, and differentially expressed genes are enriched near differential boundaries identified by TGIF. Finally, application to tissue-specific endothelial cell Hi-C datasets further demonstrates TGIF's ability to identify cell type-specific regulatory elements of interest. Taken together, TGIF is a tool to interrogate the dynamics of 3D genome organization and its impact on normal and disease phenotypes."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-06-22T16:20:22-06:00
#date_end: 2019-12-10T16:20:22-06:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2019-12-10T16:20:22-06:00

authors: ["Da-Inn Lee","Sushmita Roy"]
tags: ["Dimension Reduction","3D Genome", "Multi-task Learning"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: 
url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

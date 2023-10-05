---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Detecting higher-order structural changes in 3D genome organization with multi-task matrix factorization"
event: Intelligent Systems for Molecular Biology (ISMB)
event_url: 
location: Madison, WI 
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Three-dimensional (3D) genome organization, which determines how the DNA is packaged inside the nucleus, has emerged as a key regulatory mechanism of cellular processes. High-throughput chromosomal conformation capture (Hi-C) technologies have enabled the study of 3D genome organization by experimentally measuring interactions among genomic regions in 3D space. Analysis of Hi-C data has revealed higher-order organizational units such as topologically associating domains (TADs). Changes or disruptions to such units have been associated with disease, development, and evolution. Therefore, a key problem is to systematically detect higher-order structural changes across Hi-C datasets from multiple conditions. Existing computational methods either do not model higher-order structural units or only compare pairs of Hi-C datasets. We address these limitations with Tree-Guided Integrated Factorization (TGIF), a new multi-task Non-negative Matrix Factorization (NMF) approach. TGIF models complex relationships among multiple Hi-C datasets as a tree such that closely related Hi-C datasets have similar lower-dimensional representation. TGIF provides a statistically significant set of differential TAD boundaries with higher precision than existing approaches. Application to a cardiomyocyte differentiation timecourse dataset identified time-point specific TAD boundaries overlapping a retrotransposon element previously shown to be important for cell fate specification in humans and apes."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-07-10T16:20:22-06:00
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

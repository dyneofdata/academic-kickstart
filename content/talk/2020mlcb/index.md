---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Detecting higher-order structural changes in 3D genome organization with multi-task matrix factorization"
event: Machine Learning in Computational Biolog (MLCB) 
event_url: https://sites.google.com/cs.washington.edu/mlcb2020/
location: Virtual/online
address: 
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Three-dimensional (3D) genome organization, or how the DNA is packaged inside the nucleus, has emerged as a key regulatory mechanism of cellular function and malfunction. High-throughput chromosomal conformation capture (Hi-C) technologies have enabled the study of 3D genome organization by experimentally measuring interactions among genomic regions in 3D space. Analysis of Hi-C data has revealed higher-order organizational units at multiple resolutions: chromosomal territories, compartments, and topologically associating domains (TADs). Changes or disruptions to such structures have been associated with disease, development, and evolution. Therefore, a key problem is to systematically detect higher-order structural changes across Hi-C datasets from multiple conditions. Existing methods to address this problem are limiting in that they identify changes at individual interaction level, making them sensitive to sparsity and noise, only provide a coarse summary metric to measure differences, specialize in detecting changes at a single structural resolution, and/or offer only pairwise comparisons. We address these limitations with Tree-structured Graph-regularized Integrated Factorization (TGIF). TGIF is based on Non-negative Matrix Factorization (NMF), a dimensionality reduction method for co-clustering row and column entities of a matrix. NMF can represent a high-dimensional Hi-C matrix in low-dimensional space as clusters of genomic regions with similar interaction profiles. TGIF extends an existing multi-task framework by constraining the lower-dimensional factors from closely related tasks to be similar. Additional information about the relationship among the row entities can be encoded into a task-specific graph to constrain the factorization. We demonstrate our framework effectively recovers ground-truth clusters in simulated data and can detect biologically meaningful structural changes in Hi-C datasets from cancer cell lines and mouse neural development. "

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-11-23T16:20:22-06:00
#date_end: 2019-12-10T16:20:22-06:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2019-12-10T16:20:22-06:00

authors: ["Da-Inn Lee","Sushmita Roy"]
tags: ["Dimension Reduction","3D Genome"]

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
url_video: https://www.youtube.com/watch?v=BYanbnKpwok&t=121m30s

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

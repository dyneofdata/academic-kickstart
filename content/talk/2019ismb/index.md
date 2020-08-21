---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Discovering structural units of chromosomal organization with matrix factorization and graph regularization"
event: Intelligent Systems for Molecular Biology (ISMB)/European Conference on Computational Biology (EECB)
event_url: https://www.iscb.org/ismbeccb2019
location: Basel, Switzerland
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "The three-dimensional (3D) organization of the genome is an important layer of regulation in developmental, disease, and evolutionary processes. Hi-C is a high-throughput chromosome conformation capture (3C) assay used to study the 3D genome by measuring pairwise interactions of genomic loci.  Analysis of Hi-C data has shown that the genome is organized into higher-order organizational units such as compartments and topologically associating domains (TADs). Recent comparisons of TAD-finding methods found them to be unstable to different resolutions and sparsity levels of Hi-C data, suggesting the need for more robust methods. We present GRiNCH, a graph-regularized Non-negative Matrix Factorization (NMF) approach to identifying organizational units of chromosomes from Hi-C data. GRiNCH uses graph regularization to encourage neighboring genomic regions to belong to the same low-dimensional space. GRiNCH can recover TAD-like clusters which are significantly enriched in architectural protein binding in the boundaries and are more stable to sparse and low-depth Hi-C datasets than existing methods. Finally, GRiNCH can use the low-dimensional NMF factors to impute missing interaction counts and offer a smoothed Hi-C matrix. Taken together, GRiNCH offers a promising approach to identifying biologically meaningful structural domains of the genome."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-07-22T16:20:22-06:00
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
url_slides: 20190722_ISMB_FINAL.pdf
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

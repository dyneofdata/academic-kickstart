---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Detecting dynamic 3D genome organization with multi-task matrix factorization"
event: Research in Computational Molecular Biology (RECOMB) / Regulatory and Systems Genomics with DREAM Challenges (RSGDREAM) 
event_url: 
location: Las Vegas, NV 
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "The three-dimensional (3D) organization of the genome, which determines how the DNA is packaged inside the nucleus, has emerged as a key regulatory mechanism of cellular function and malfunction. High-throughput chromosomal conformation capture (Hi-C) technologies have enabled the study of 3D genome organization by experimentally measuring the tendency of genomic regions to interact with one another in 3D space. Changes or disruptions to the 3D genome organization have been associated with disease, developmental, and evolutionary processes. Therefore, a key problem in regulatory genomics is to systematically detect higher-order structural changes across Hi-C datasets from multiple timepoints and conditions. Existing methods to detect changes in 3D genome organization are limiting in one or more ways: they identify changes at the individual interaction level, they offer only pairwise comparison between two datasets at a time, or they do not account for more complex nested relationships among the conditions represented by the datasets. We address these limitations with a new approach, Tree-Guided Integrated Factorization (TGIF) to examine the dynamics of topologically associating domain (TAD) boundaries. TGIF is based on hierarchical multi-task Non-negative Matrix Factorization (NMF), a dimensionality reduction method particularly useful for co-clustering the row and the column entities of a matrix. TGIF takes as input Hi-C matrices from multiple related biological conditions, for example, different cell types from a cell lineage. TGIF constrains the lower-dimensional factors from closely related tasks (e.g. cell types derived from the same “parent” of the cell lineage) to be similar. The output factor matrices represent the lower-dimensional view of the chromosomal architecture. We use these low-dimensional views to calculate a TAD boundary score for each region and identify differential or common boundaries across all conditions. Compared to existing approaches, TGIF recovers ground-truth differential TAD boundaries with higher precision in simulated data and is also less susceptible to identifying spurious boundaries due to variation in dataset depth. We applied TGIF to study across multiple cell types as well as across a time course.  From a cardiomyocyte differentiation time course data, TGIF identified embryonic-stage-specific TAD boundaries associated with transcriptionally active HERV-H retrotransposon; such sites are known to demarcate TAD boundaries in human and ape pluripotent cells. We further identify transcription factor motifs enriched in embryonic-stage-specific boundary regions and demonstrate that cardiovascular-disease associated GWAS SNPs are depleted in such boundary regions. Together, these results demonstrate the utility of TGIF to identify biologically meaningful topological shifts in genome organization."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-11-10T16:20:22-06:00
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

---
title: "GRINCH: Discovering structural units of chromosomes with graph-regularized matrix factorization"
poster: true
event: Research in Computational Molecular Biology (RECOMB) / Regulatory and Systems Genomics with DREAM Challenges (RSGDREAM)
event_url: https://www.iscb.org/recomb-regsysgen2018
location: New York City, United States
summary: ""
abstract: "Three dimensional organization of the genome is emerging as an important determinant of cell-type specific expression and is implicated in many diseases, including cancer (Bouwman & de Laat 2015). Hi-C is a type of high-throughput chromosome conformation capture (3C) assay which can be used to study the three-dimensional organization of chromosomes (Lieberman-Aiden et al. 2009).  Analysis of Hi-C data can reconstruct the building blocks that give rise to or result from the organizational principles of the genome: topologically associating domains (TADs), transcriptionally active compartments, chromatin loops, chromosomal territories (Gibcus & Dekker 2013). Recent studies comparing TAD-finding methods (Forcato et al. 2017, Dali & Blanchette 2017) found the methods to vary significantly in their replicability and stability across sequence depth, sparsity, and resolution of the input data, suggesting the need for more robust methods. <br> Here we present GRiNCH, an approach based on Non-Negative Matrix Factorization (NMF) to identify organizational units of chromosomes from Hi-C data. NMF is a powerful dimensionality-reduction technique that can recover low-dimensional representations of images, texts, and biological data (Lee & Seung 2000). GRiNCH extends the NMF framework by using a graph regularization term that (Cai et al. 2011) encourages nearby genomic regions in similar chromatin state or with similar insulator binding pattern to converge to a similar low-dimensional state. Our results show that GRiNCH can recover clusters with TAD-like properties whose boundaries show a significant association with the presence of CTCF binding. Compared to existing TAD-finding methods, GRiNCH clusters are more stable to sparse and low-depth Hi-C datasets. Finally, through a matrix completion process, GRiNCH can impute missing interaction counts and offer a smoothed Hi-C matrix comparable in quality to smoothing process employed by methods like HiCRep (Yang et al. 2017). Taken together, GRiNCH offers a promising approach to mining biologically meaningful structural domains of the genome."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2018-12-10T13:00:00"
#date_end: "2018-12-10T15:00:00"
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

#links: 
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


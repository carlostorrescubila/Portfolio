---
title: "Sparse HJ Biplot: A New Methodology via Elastic Net"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mitzi Cubilla-Montilla
- Ana Belén Nieto-Librero
- M. Purificación Galindo-Villardón
- admin

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2021-06-05"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Mathematics*, 9(11)"
publication_short: ""

abstract: The HJ biplot is a multivariate analysis technique that allows us to represent both individuals and variables in a space of reduced dimensions. To adapt this approach to massive datasets, it is necessary to implement new techniques that are capable of reducing the dimensionality of the data and improving interpretation. Because of this, we propose a modern approach to obtaining the HJ biplot called the elastic net HJ biplot, which applies the elastic net penalty to improve the interpretation of the results. It is a novel algorithm in the sense that it is the first attempt within the biplot family in which regularisation methods are used to obtain modified loadings to optimise the results. As a complement to the proposed method, and to give practical support to it, a package has been developed in the R language called SparseBiplots. This package fills a gap that exists in the context of the HJ biplot through penalized techniques since in addition to the elastic net, it also includes the ridge and lasso to obtain the HJ biplot. To complete the study, a practical comparison is made with the standard HJ biplot and the disjoint biplot, and some results common to these methods are analysed. 

# Summary. An optional shortened abstract.
summary: New proposal for obtaining the HJ biplot by applying the elastic net penalty to improve the interpretation of the results.

tags: ["biplot", "sparse", "PCA",  "regularization",  "elastic net",  "multivariate analysis",  "R Software", "TCGA", "breast cancer"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- icon: pager
  icon_pack: fas
  name: Journal
  url: https://www.mdpi.com/journal/mathematics
- icon: doi
  icon_pack: ai
  name: DOI
  url: https://doi.org/10.3390/math9111298
- icon: file-pdf
  icon_pack: fas
  name: PDF
  url: https://www.mdpi.com/2227-7390/9/11/1298/pdf
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---

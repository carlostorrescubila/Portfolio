---
title: SparseBiplots
summary: R package that performs the HJ-Biplot and modifications introducing Ridge, LASSO and Elastic Net penalty.
tags:
- R
- Library
- Biplot
- Multivariate Analysis
date: "2021-10-23"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: r-project
  icon_pack: fab
  name: RDocumentation
  url: https://www.rdocumentation.org/packages/SparseBiplots/versions/4.0.1
- icon: github
  icon_pack: fab
  name: Repository
  url: https://github.com/mitzicubillamontilla/SparseBiplots
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

Sparse Biplots are modern variant of HJ-Biplot which attempts to find sparse loadings, i.e., weight vectors with only a few nonzero values. Introducing a penalty parameter helps improve the interpretation of the model because the axis are formed as a linear combination of only some of the original variables.

This package provides functions to perform the HJ-Biplot (Galindo, 1986) and modifications introducing Ridge, LASSO and Elastic Net penalty

---
title: SparseBiplots
summary: Paquete R que realiza el HJ-Biplot y las modificaciones introduciendo la penalización Ridge, LASSO y Elastic Net.
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
  name: Repositorio
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

Los *Sparse Biplots* son una variante moderna del HJ-Biplot que intenta encontrar cargas dispersas, es decir, vectores de pesos con sólo unos pocos valores distintos de cero. La introducción de un parámetro de penalización ayuda a mejorar la interpretación del modelo porque los ejes se forman como una combinación lineal de sólo algunas de las variables originales.

Este paquete proporciona funciones para realizar el HJ-Biplot y modificaciones que introducen la penalización Ridge, LASSO y Elastic Net.

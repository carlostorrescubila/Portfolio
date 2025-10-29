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

abstract: El HJ biplot es una técnica de análisis multivariante que permite representar tanto a los individuos como a las variables en un espacio de dimensiones reducidas. Para adaptar este enfoque a conjuntos de datos masivos, es necesario implementar nuevas técnicas que sean capaces de reducir la dimensionalidad de los datos y mejorar la interpretación. Por ello, proponemos un enfoque moderno para la obtención del HJ biplot denominado elastic net HJ biplot, que aplica la penalización elastic net para mejorar la interpretación de los resultados. Se trata de un algoritmo novedoso en el sentido de que es el primer intento dentro de la familia de biplots en el que se utilizan métodos de regularización para obtener cargas modificadas que optimicen los resultados. Como complemento al método propuesto, y para darle soporte práctico, se ha desarrollado un paquete en el lenguaje R llamado SparseBiplots. Este paquete cubre un vacío existente en el contexto del HJ biplot mediante técnicas penalizadas ya que además de la penalización elastic net, incluye las penalizaciones ridge y el lasso para obtener el HJ biplot. Para completar el estudio, se realiza una comparación práctica con el HJ biplot estándar y el disjoint biplot, y se analizan algunos resultados comunes a estos métodos

# Summary. An optional shortened abstract.
summary: Nueva propuesta para la obtención del HJ biplot aplicando la penalización elastic net para mejorar la interpretación de los resultados.

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

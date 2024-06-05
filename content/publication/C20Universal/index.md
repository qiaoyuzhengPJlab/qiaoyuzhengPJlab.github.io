---
title: "FTL: A universal framework for training low-bit DNNs via Feature Transfer"
authors:
- K. Du
- Y. Zhang
- H. Guan
- Q. Tian
- Y. Wang*
- S. Cheng
- J. Lin
date: "2020-11-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ECCV 2020"
publication_short: ""

abstract: Low-bit Deep Neural Networks (low-bit DNNs) have recently received significant attention for their high efficiency. However, low-bit DNNs are often difficult to optimize due to the saddle points in loss surfaces. Here we introduce a novel feature-based knowledge transfer framework, which utilizes a 32-bit DNN to guide the training of a low-bit DNN via feature maps. It is challenge because feature maps from two branches lie in continuous and discrete space respectively, and such mismatch has not been handled properly by existing feature transfer frameworks. In this paper, we propose to directly transfer information-rich continuous-space feature to the low-bit branch...
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: https://link.springer.com/chapter/10.1007/978-3-030-58595-2_42
url_pdf: https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700698.pdf
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

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
slides: example
---

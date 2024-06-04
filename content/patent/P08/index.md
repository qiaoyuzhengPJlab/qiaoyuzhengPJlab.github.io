---
title: "一种有监督深度哈希快速图片检索方法及系统，申请专利号：CN201710555687.9（已授权）" 
authors:
- 王延峰*
- 周越夫
- 黄衫衫
- 张娅


date: "2017-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提出一种有监督深度哈希快速图片检索方法及系统,方法包括:构建用于快速图像检索的深度卷积神经网络H″;将图库中的图片依次输入深度卷积神经网络H″后得到实值特征,经过量化操作后得到哈希码并储存在本地;将每一张查询图片q输入至深度卷积神经网络H″并量化得到哈希码h(q),再计算哈希码h(q)与所有存储在本地的哈希码之间的汉明距离,将汉明距离为小的认作相似度为高,以此进行排序,最终根据检索数量要求返回相应数量的最为相似的图片.本发明基于现有的深度神经网络,利用三元组标签数据进行图片特征表达的学习采用三元组量化损失函数,用于构建有监督深度哈希模型,从而实现既快速又精准的图片检索.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=171v0m10yy0m0000ph2m0gw056528932&site=xueshu_se&hitarticle=1
# url_pdf: http://arxiv.org/pdf/1512.04133v1
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

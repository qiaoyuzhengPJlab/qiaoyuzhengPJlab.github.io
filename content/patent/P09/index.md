---
title: "基于自训练和切片传播的弱监督脊椎椎体分割方法和系统，申请专利号：CN201910989817.9" 
authors:
- 王延峰*
- 彭诗奇
- 张娅
- 赵晖
- 顾一峰
- 李跃华
- 姚光宇


date: "2020-03-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提供了一种基于自训练和切片传播的弱监督脊椎椎体分割方法和系统,从病人的CT图像数据中获取每一张矢状面切片;以正中矢状面切片上每块脊骨的四个顶点作为标签,训练一个Mask RCNN分割网络;使用自训练的方法,并结合置信区域选择与条件随机场,来优化训练集标签;使用切片传播的方法,不断地扩充训练集,继续同一个分割网络,直至收敛.本发明能够仅通过一张矢状面的脊骨四个顶点标签,训练一个能对全部矢状面进行预测的分割模型,从而完成对脊椎椎体的三维分割.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=1n2q0mx091640vg0570902n0dv235993&site=xueshu_se&hitarticle=1
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

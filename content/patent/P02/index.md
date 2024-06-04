---
title: "适用于脊柱转移肿瘤骨质的质量分类方法及系统，申请专利号：CN201910881871.1" 
authors:
- 王延峰*
- 彭诗奇
- 张娅
- 赵晖
- 顾一峰
- 李跃华
- 姚光宇

date: "2020-01-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-03T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提供了一种适用于脊柱转移肿瘤骨质的质量分类方法及系统,所述方法包括:从DICOM文件中获取病人的CT图像数据,根据阈值提取的方法裁剪出脊椎椎体的区域;将骨质质量分类任务建模为成骨分类子任务和溶骨分类子任务,并使用多层感知机将两个子任务的结果进行合并;对于每一张横截面的CT图像,使用多任务学习的方式,同时学习骨质质量分类任务和后外侧受损情况分类任务,并共享不同任务的特征图;使用自步学习的方式,让模型优先学习容易的样本,再逐渐学习较为困难的样本.本发明通过同时学习多个相关的任务并特征共享,以及使用从易到难的自步学习方法,实现了对脊柱转移肿瘤骨质质量的精确分类.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=183j0jx0q66p0mb01u5608p0sb239592&site=xueshu_se&hitarticle=1
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

---
title: "脊骨脱位辅助诊断方法及系统" 
authors:
- 王延峰*
- 赖柏霖
- 张小云
date: "2020-01-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-07T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提供了一种脊骨脱位辅助诊断方法及系统,所述方法包括:粗分割网络训练步骤:通过少量标注了脊骨椎体四个顶点的数据训练粗略的分割网络;滑窗提取步骤:对输入图像按照其中脊骨椎体的大小提取滑窗进行数据增广;特征提取步骤:对于输入的医疗影像通过深度神经网络提取高层语义特征;类别激活图生成步骤:利用分类网络中已有的参数生成类别激活图;专家知识引导步骤:利用分割网络得到粗略分割结果定位前后边缘的大致位置,并以此约束神经网络类别激活图中的概率分布.本发明对于脊骨脱位诊断的准确率和可解释性,并且在数据量较小时能保持很好的性能.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=1a470xa0x33d0vy06u140j206a513538&site=xueshu_se
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

---
title: "交互式图像分割方法、系统及终端，申请专利号：CN201911405917.9" 
authors:
- 张娅
- 廖选
- 李文浩
- 徐琪森
- 王祥丰
- 金博
- 张小云
- 王延峰* 


date: "2019-12-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-12-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提供了一种交互式图像分割方法,系统及终端,所述方法包括:S1,获取图像的初始分割结果;S2,根据当前图像分割结果选择至少一个错误区域,对每个错误区域的中心点进行标记,作为交互提示点;S3,计算图像上各点与每个所述交互提示点之间的距离生成提示图;S4,根据当前图像分割结果和所述提示图,利用深度增强学习全卷积神经网络调整分割概率,对当前图像分割结果进行改善,得到图像分割改善结果;S5,对所述图像分割改善结果进行评价,若满意则作为最终图像分割结果,若不满意则重新回到S2,进行迭代更新.本发明能辅助专家进行图像分割标注,减轻了专家的标注负担,提高了标注的性能和效率.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=166q08r07w7g0v60gq2r00s0b6788446&site=xueshu_se
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

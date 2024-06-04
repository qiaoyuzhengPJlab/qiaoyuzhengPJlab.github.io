---
title: "基于变分推断的逐层神经网络剪枝方法和系统，申请专利号：CN201910195272.4" 
authors:
- 王延峰*
- 周越夫
- 张娅

date: "2019-07-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提供了一种基于变分推断的逐层神经网络剪枝方法和系统,该方法包括:通过采样方式在神经网络中注噪声,得到噪化的神经网络;根据预设的目标函数对噪化的神经网络的权重进行训练,得到训练后的神经网络权重和训练后的神经网络;根据变分推断得到的变分下界,训练注入的乘性高斯噪声对应的噪声参数,得到训练后的噪声参数;基于所述训练后的噪声参数,训练后的神经网络权重,通过阈值函数逐层删除所述训练后的神经网络中相应的神经元或者卷积核.本发明的方法中,所注入的噪声在训练过程中融入了神经网络的层级关系,使得在剪枝过程中充分考虑层间的依赖,继而保证了在高度剪枝下神经网络的输出结果依旧具备鲁棒性.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=1q270p704m2q068015400ep0fm081408&site=xueshu_se&hitarticle=1
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

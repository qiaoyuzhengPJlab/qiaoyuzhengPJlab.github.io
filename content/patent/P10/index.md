---
title: "约束时域关系的视频动作定位方法和系统，申请专利号：CN202010032794.5" 
authors:
- 张娅
- 赵培森
- 王延峰* 


date: "2020-06-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提供一种约束时域关系的视频动作定位方法和系统，包括：视频特征提取步骤：对输入的未经裁剪的长视频，使用3D深度神经网络提取其特征，得到能够表达视频语义信息的特征序列；动作曲线预测步骤：利用提取好的视频特征序列训练动作概率曲线模型，预测视频中动作的开始、持续、结束的概率曲线；动作曲线约束步骤：在训练动作概率曲线模型的过程中同时约束动作的开始、持续、结束的概率曲线，使其有平稳连续的输出并且使动作的开始、持续、结束的概率曲线峰值遵循合理的时间顺序。本发明对输入的视频进行逐个时刻的动作概率预测，重点约束动作在时间维度上的关系，通过在模型的训练过程中加入约束，使得其能够准确地预测动作发生的概率，从而能够精确的定位视频中所发生的动作。
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=1g660mb0xe1t06g0417e0pu0nr143246&site=xueshu_se&hitarticle=1
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

---
title: "一种基于自适应采样策略的弱监督视频时序动作检测方法和系统，申请专利号：CN202010403823.4" 
authors:
- 张娅
- 鞠陈
- 王延峰* 


date: "2020-09-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提供了一种基于自适应采样的弱监督时序动作检测方法及系统,包括:根据输入的视频提取视频特征图;将视频特征图映射成均匀分布类别激活序列;根据均匀分布类别激活序列产生伯努利数列作为自适应重采样位置索引;对视频特征图进行特征重采样;将视频重采样特征图映射成非均匀分布类别激活序列;对均匀和非均匀分布类别激活序列使用分类网络预测视频为各个类别的概率;对非均匀分布类别激活序列进行分布均匀化,从而和均匀分布类别激活序列在时间分布上对齐;选择对齐后的均匀或非均匀分布类别激活序列使用阈值法得到视频的检测结果.本发明对输入视频提取两种相互补充,互相监督的类别激活映射序列,实现更精确的弱监督的视频时序动作检测.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=1e3c0j10ar5n0vf0bx180tg0xv068645&site=xueshu_se&hitarticle=1
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

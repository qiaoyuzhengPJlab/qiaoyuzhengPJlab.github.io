---
title: "一种用于STL/SFN传输的RTP协议封装方法，申请专利号：CN201710327818.8" 
authors:
- 王延峰*
- 熊帅
- 刘宜璠
- 徐胤
- 何大治


date: "2020-12-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
# publication: "前沿科学"
publication_short: ""

abstract: 本发明提供了一种用于STL/SFN传输的RTP协议封装方法,包括:在封装RTP数据包时,对两层原有的RTP协议字段进行整合,传输时只需进行外层RTP协议封装.将外层RTP协议的补偿字段划分出16比特表示里层RTP用于指示BBP报文长度的字段,并用其指示封装后的RTP报文总长,其他相同字段的功能也整合到外层RTP协议报头中.本发明的方案在不影响各层协议传输功能的前提下,精简了协议架构,提高了STL传输尤其是软件数据并行传输方案下的传输效率.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: false

links:
- name: Custom Link
  url: https://xueshu.baidu.com/usercenter/paper/show?paperid=1y560jq0hx560tk08p3w0j00ym420595&site=xueshu_se&hitarticle=1
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

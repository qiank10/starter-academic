---
title: "Widar2.0: Passive Human Tracking with a Single Wi-Fi Link"

authors:
- Kun Qian
- Chenshu Wu
- Yi Zhang
- Guidong Zhang
- Zheng Yang
- Yunhao Liu

date: 2018-06-10T00:00:00.000Z
doi: ""

publication_types:
  - "1"

publication: In Proceedings of ACM MobiSys 2018
publication_short: In ACM MobiSys

abstract: 'This paper presents Widar2.0, the first WiFi-based system that enables passive human localization and tracking using a single link on commodity off-the-shelf devices. Previous works based on either specialized or commercial hardware all require multiple links, preventing their wide adoption in scenarios like homes where typically only one single AP is installed. The key insight underlying Widar2.0 to circumvent the use of multiple links is to leverage multi-dimensional signal parameters from one single link. To this end, we build a unified model accounting for Angle-of-Arrival, Time-of-Flight, and Doppler shifts together and devise an efficient algorithm for their joint estimation. We then design a pipeline to translate the erroneous raw parameters into precise locations, which first finds parameters corresponding to the reflections of interests, then refines range estimates, and ultimately outputs target locations. Our implementation and evaluation on commodity WiFi devices demonstrate that Widar2.0 achieves better or comparable performance to state-of-the-art localization systems, which either use specialized hardwares or require 2 to 40 Wi-Fi links.'

tags:
  - "Wireless Sensing"

draft: false
featured: false

url_pdf: 'https://www.dropbox.com/s/t931e50ppveqzoc/MobiSys18_Widar2.0_paper.pdf?dl=0'
url_code: ''
url_dataset: 'http://tns.thss.tsinghua.edu.cn/wifiradar'
url_poster: ''
url_project: ''
url_slides: 'https://www.dropbox.com/s/i2f30pzf7qrzajq/MobiSys18_Widar2.0_slides.pptx?dl=0'
url_source: ''
url_video: ''

image:
  caption: "High-level design of Widar2.0."
  filename: featured
  focal_point: Smart
  preview_only: false

projects:
- human-oriented-wireless-sensing
---

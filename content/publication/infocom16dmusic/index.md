---
title: "Tuning by Turning: Enabling Phased Array Signal Processing for WiFi with Inertial Sensors"

authors:
- Kun Qian
- Chenshu Wu
- Zheng Yang
- Zimu Zhou
- Xu Wang
- Yunhao Liu

date: 2016-04-10T00:00:00.000Z
doi: ""

publication_types:
  - "1"

publication: In Proceedings of IEEE INFOCOM 2016
publication_short: In IEEE INFOCOM

abstract: 'Modern mobile devices are equipped with multiple antennas, which brings various wireless sensing applications such as accurate localization, contactless human detection and wireless human-device interaction. A key enabler for these applications is phased array signal processing, especially Angle of Arrival (AoA) estimation. However, accurate AoA estimation on commodity devices is non-trivial due to limited number of antennas and uncertain phase offsets. Previous works either rely on elaborate calibration or involve contrived human interactions. In this paper, we aim to enable practical AoA measurements on commodity off-the-shelf (COTS) mobile devices. The key insight is to involve users’ natural rotation to formulate a virtual spatial-temporal antenna array and conduce a relative incident signal of measurements at two orientations. Then by taking the differential phase, it is feasible to remove the phase offsets and derive the accurate AoA of the equivalent incoming signal, while the rotation angle can also be captured by built-in inertial sensors. On this basis, we propose Differential MUSIC (D-MUSIC), a relative form of the standard MUSIC algorithm that eliminates the unknown phase offsets and achieves accurate AoA estimation on COTS mobile devices with only one rotation. We further extend D-MUSIC to 3-D space and fortify it in multipath-rich scenarios. We prototype D-MUSIC on commodity WiFi infrastructure and evaluate it in typical indoor environments. Experimental results demonstrate a superior performance with an average AoA estimation error of 13◦ . Requiring no modifications or calibration, D-MUSIC is envisioned as a promising scheme for practical AoA estimation on COTS mobile devices.'

tags:
  - "Wireless Sensing"
  - "Mobile Computing"

draft: false
featured: false

url_pdf: 'https://www.dropbox.com/s/mpi43v0i5knjjxh/INFOCOM16_TuningbyTurning_paper.pdf?dl=0'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.dropbox.com/s/e1at1cxqs5lqq8f/INFOCOM16_TuningByTurning_slides.pptx?dl=0'
url_source: ''
url_video: ''

image:
  caption: "Principle of D-MUSIC."
  filename: featured
  focal_point: Smart
  preview_only: false
---

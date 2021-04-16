---
title: "AIRCODE: Hidden Screen-Camera Communication on an Invisible and Inaudible Dual Channel"

authors:
- Kun Qian
- Yumeng Lu
- Zheng Yang
- Kai Zhang
- Kehong Huang
- Xinjun Cai
- Chenshu Wu
- Yunhao Liu

date: 2021-04-12T00:00:00.000Z
doi: ""

publication_types:
  - "1"

publication: In Proceedings of USENIX NSDI 2021
publication_short: In USENIX NSDI

abstract: 'Hidden screen-camera communication emerges as a key enabler for the next generation videos that allow side information, such as TV commercials, augmented contents, and even the video itself, to be delivered to machines during normal watching. To guarantee imperceptibility to human eyes, existing solutions have to sacrifice data rate and reliability enormously. This paper presents AIRCODE, a hidden screencamera communication system built upon invisible visual and inaudible audio dual channel. While ensuring great unobtrusiveness, AIRCODE achieves robust communication at a remarkably high rate of >1Mbps, for the first time, enabling imperceptible transmission of not only texts but also videos. AIRCODE makes two key technical contributions. First, AIRCODE takes the complementary advantages of video and audio channels by exploiting the reliable yet low-rate inaudible audio link as the control channel while the unreliable but high-rate visual link as the data channel. Second, AIRCODE incorporates visual odometry to accurately identify and track the captured screen, regardless of dynamic video contents and surrounding interference. Experiments on commercial monitors and smartphones demonstrate that AIRCODE significantly outperforms the state-of-the-art system, yielding a remarkable data rate of 1069 Kbps while with BER of 5%.'

tags:
  - "Mobile Computing"

draft: false
featured: false

url_pdf: 'https://www.dropbox.com/s/4z5c4tabshved46/NSDI21_AirCode_paper.pdf?dl=0'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.dropbox.com/s/n6y3q5s7mmypenz/NSDI21_AirCode_slides.pptx?dl=0'
url_source: ''
url_video: ''

image:
  caption: "System overview of AIRCODE. The monitor displays a video with embedded data in raw video frames, and metadata (control information) in raw audio signals. The phone records the video, then detects screen in camera images to equalize distorted video frames, decodes metadata from audio signals, and finally decodes data embedded in video."
  filename: featured
  focal_point: Smart
  preview_only: false
---

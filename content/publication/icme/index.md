---
title: "EVAN: Evolutional Video Streaming Adaptation via Neural Representation"
authors:
- admin
date: "2023-12-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "ICME 2024"
publication_short: ""

abstract: Adaptive bitrate (ABR) using conventional codecs cannot further modify the bitrate once a decision has been made, exhibiting limited adaptation capability. This may result in either overly conservative or overly aggressive bitrate selection, which could cause either inefficient utilization of the network bandwidth or frequent re-buffering, respectively. Neural representation for video (NeRV), which embeds the video content into neural network weights, allows video reconstruction with incomplete models. Specifically, the recovery of one frame can be achieved without relying on the decoding of adjacent frames. NeRV has the potential to provide high video reconstruction quality and, more importantly, pave the way for developing more flexible ABR strategies for video transmission. In this work, a new framework, named Evolutional Video streaming Adaptation via Neural representation (EVAN), which can adaptively transmit NeRV models based on soft actor-critic (SAC) reinforcement learning, is proposed. EVAN is trained with a more exploitative strategy and utilizes progressive playback to avoid re-buffering. Experiments showed that EVAN can outperform existing ABRs with 50% reduction in re-buffering and achieve nearly 20% improvement in users’ quality of experience (QoE).

# Summary. An optional shortened abstract.
summary: We proposed EVAN, an adaptive video streaming system that utilizes neural video representations (NeRV). This system is distinct from ABR approaches that use conventional codecs, as it is trained with a more effective strategy and progressive playback is used to prevent re-buffering.

tags:
- Video streaming
featured: True

# links:
# - name: Custom Link
  # url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/Evan-sudo/Soft-ACK-based-Outer-Loop-Link-Adaptation-for-Latency-constrained-5G-Video-Conferencing'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

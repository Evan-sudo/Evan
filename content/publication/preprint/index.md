---
title: "Soft-ACK based Outer Loop Link Adaptation for Latency-constrained 5G Video Conferencing"
authors:
- admin
# date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "GlobeCom 2023"
publication_short: ""

abstract: The high reliability and low latency requirements of multimedia services necessitate the design of more efficient link adaptation methods. In this paper, we introduce instantaneous channel state information (CSI) reporting, specifically designed for 5G video conferencing, and enhance the outer loop link adaptation based on soft Acknowledgement (Soft-ACK). We also formulate a resource allocation problem in 5G physical downlink shared channel (PDSCH) to balance the uplink and downlink traffic in compliance with the specified latency constraints. Our proposed scheme operates in a relatively straightforward manner. It outperforms conventional link adaptation methods regarding Block-Level Error Rate (BLER) and effectively adheres to stringent latency constraints in video transmission simulations.

# Summary. An optional shortened abstract.
summary: We present a soft-ACK-based outer loop link adaptation scheme for 5G NR video conferencing. By leveraging instantaneous CSI reporting and soft-ACK, we have significantly reduced the overhead of channel control, allowing the traditional link adaptation mechanism to converge faster to lower BLER levels. Moreover, the formulated resource allocation problem effectively manages the downlink transmission resources while meeting stringent latency requirements, resulting in a balanced uplink and downlink traffic state. Performance simulations on the Waterloo QoE database validate the effectiveness of the proposed approach, showing a significant overhead saving (0.8% of conventional CSI-RS) in CSI reporting while ensuring the reliability requirements of video conferencing. We believe this approach can be extended to scenarios involving multi-service flows under 6G carrier aggregation, leveraging multimodal channel feedback combined with state-of-the-art AI technologies for more accurate link prediction and control.

tags:
- Wireless Communication
featured: True

links:
- name: Custom Link
  # url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

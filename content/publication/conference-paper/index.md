---
title: "Soft-ACK based Outer Loop Link Adaptation for Latency-constrained 5G Video Conferencing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
# authors:
#   - admin
#   - Robert Ford

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-12-04'
doi: ''

# # Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *GlobeCom*
# publication_short: In *ICW*

abstract: The high reliability and low latency requirements of multimedia services necessitate the design of more efficient link adaptation methods. In this paper, we introduce instantaneous channel state information (CSI) reporting, specifically designed for 5G video conferencing, and enhance the outer loop link adaptation based on soft Acknowledgement (Soft-ACK). We also formulate a resource allocation problem in 5G physical downlink shared channel (PDSCH) to balance the uplink and downlink traffic in compliance with the specified latency constraints. Our proposed scheme operates in a relatively straightforward manner. It outperforms conventional link adaptation methods regarding Block-Level Error Rate (BLER) and effectively adheres to stringent latency constraints in video transmission simulations.

# Summary. An optional shortened abstract.
summary: We present a soft-ACK-based outer loop link adaptation scheme for 5G NR video conferencing. By leveraging instantaneous CSI reporting and soft-ACK, we have significantly reduced the overhead of channel control, allowing the traditional link adaptation mechanism to converge faster to lower BLER levels. Moreover, the formulated resource allocation problem effectively manages the downlink transmission resources while meeting stringent latency requirements, resulting in a balanced uplink and downlink traffic state. Performance simulations on the Waterloo QoE database validate the effectiveness of the proposed approach, showing a significant overhead saving (0.8% of conventional CSI-RS) in CSI reporting while ensuring the reliability requirements of video conferencing. We believe this approach can be extended to scenarios involving multi-service flows under 6G carrier aggregation, leveraging multimodal channel feedback combined with state-of-the-art AI technologies for more accurate link prediction and control.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

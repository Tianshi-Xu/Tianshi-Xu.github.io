---
title: 'Falcon: Accelerating Homomorphically Encrypted Convolutions for Efficient Private Mobile Network Inference'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Meng Li
  - Runsheng Wang
  - Ru Huang

# Author notes (optional)
author_notes:


date: '2023-10-28T00:00:00Z'
doi: '10.1109/ICCAD57390.2023.10323672'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-28T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE/ACM International Conference on Computer Aided Design
publication_short: ICCAD 2023

abstract: Efficient networks, e.g., MobileNetV2, EfficientNet, etc, achieves state-of-the-art (SOTA) accuracy with lightweight computation. However, existing homomorphic encryption (HE)-based two-party computation (2PC) frameworks are not op-timized for these networks and suffer from a high inference overhead. We observe the inefficiency mainly comes from the packing algorithm, which ignores the computation character-istics and the communication bottleneck of homomorphically encrypted depthwise convolutions. Therefore, in this paper, we propose Falcon, an effective dense packing algorithm for HE-based 2PC frameworks. Falcon features a zero-aware greedy packing algorithm and a communication-aware operator tiling strategy to improve the packing density for depth wise convo-lutions. Compared to SOTA HE-based 2PC frameworks, e.g., CrypTFlow2, Iron and Cheetah, Falcon achieves more than 15.6 x, 5.1 x and 1.8 x latency reduction, respectively, at operator level. Meanwhile, at network level, Falcon allows for 1.4 % and 4.2% accuracy improvement over Cheetah on CIFAR-100 and Tiny Imagenet datasets with iso-communication, respectively.

# Summary. An optional shortened abstract.
summary: 

tags: [conference]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper Link
  url: https://arxiv.org/pdf/2308.13189.pdf

url_pdf: 'https://arxiv.org/pdf/2308.13189.pdf'
url_code: 
url_dataset: 
url_poster: 
url_project: 
url_slides: 
url_source: 
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

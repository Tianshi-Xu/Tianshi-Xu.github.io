---
title: 'FastQuery: Communication-efficient Embedding Table Query for Private LLM Inference'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chenqi Lin
  - admin 
  - Zebin Yang
  - Runsheng Wang
  - Ru Huang
  - Meng Li

# Author notes (optional)
author_notes:


date: '2024-05-25T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2024 IEEE/ACM Design Automation Conference
publication_short: DAC 2024

abstract: With the fast evolution of large language models (LLMs), privacy concerns with user queries arise as they may contain sensitive information. Private inference based on homomorphic encryption (HE) has been proposed to protect user query privacy. However, a private embedding table query has to be formulated as a HE-based matrix-vector multiplication problem and suffers from enormous computation and communication overhead. We observe the overhead mainly comes from the neglect of 1) the one-hot nature of user queries and 2) the robustness of the embedding table to low bit-width quantization noise. Hence, in this paper, we propose a private embedding table query optimization framework, dubbed FastQuery. FastQuery features a communication-aware embedding table quantization algorithm and a one-hot-aware dense packing algorithm to simultaneously reduce both the computation and communication costs. Compared to prior-art HE-based frameworks, e.g., Cheetah, Iron, and Bumblebee, FastQuery achieves more than 4.3×, 2.7×, 1.3× latency reduction, respectively and more than 75.7×, 60.2×, 20.2× communication reduction, respectively, on both LLAMA-7B and LLAMA-30B.

# Summary. An optional shortened abstract.
summary: 

tags: [conference]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper Link
  url: https://arxiv.org/abs/2405.16241

url_pdf: 'https://arxiv.org/pdf/2405.16241'
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

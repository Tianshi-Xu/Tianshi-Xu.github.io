---
title: "HEQuant: Marrying Homomorphic Encryption and Quantization for Communication-Efficient Private Inference"
authors:
- admin
- Meng Li
- Runsheng Wang
date: "2024-01-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Secure two-party computation with homomorphic encryption (HE) protects data privacy with a formal security guarantee but suffers from high communication overhead. While previous works, e.g., Cheetah, Iron, etc, have proposed efficient HE-based protocols for different neural network (NN) operations, they still assume high precision, e.g., fixed point 37 bit, for the NN operations and ignore NNs' native robustness against quantization error. In this paper, we propose HEQuant, which features low-precision-quantization-aware optimization for the HE-based protocols. We observe the benefit of a naive combination of quantization and HE quickly saturates as bit precision goes down. Hence, to further improve communication efficiency, we propose a series of optimizations, including an intra-coefficient packing algorithm and a quantization-aware tiling algorithm, to simultaneously reduce the number and precision of the transferred data. Compared with prior-art HE-based protocols, e.g., CrypTFlow2, Cheetah, Iron, etc, HEQuant achieves $3.5\sim 23.4\times$ communication reduction and $3.0\sim 9.3\times$ latency reduction. Meanwhile, when compared with prior-art network optimization frameworks, e.g., SENet, SNL, etc, HEQuant also achieves $3.1\sim 3.6\times$ communication reduction.

# Summary. An optional shortened abstract.
summary: 

tags:
- arXiv/Preprint
featured: false

links:
- name: Paper Link
  url: https://arxiv.org/abs/2401.15970
url_pdf: https://arxiv.org/pdf/2401.15970.pdf
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
  focal_point: ""
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
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

---
title: "PrivCirNet: Efficient Private Inference via Block Circulant Transformation"
authors:
- admin
- Lemeng Wu
- Runsheng Wang
- Meng Li
date: "2024-05-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: Neural Information Processing Systems 2024 
publication_short: NeurIPS 2024

abstract: Homomorphic encryption (HE)-based deep neural network (DNN) inference protects data and model privacy but suffers from significant computation overhead. We observe transforming the DNN weights into circulant matrices converts general matrix-vector multiplications into HE-friendly 1-dimensional convolutions, drastically reducing the HE computation cost. Hence, in this paper, we propose \method, a protocol/network co-optimization framework based on block circulant transformation. At the protocol level, PrivCirNet customizes the HE encoding algorithm that is fully compatible with the block circulant transformation and reduces the computation latency in proportion to the block size. At the network level, we propose a latency-aware formulation to search for the layer-wise block size assignment based on second-order information. PrivCirNet also leverages layer fusion to further reduce the inference cost. We compare PrivCirNet with the state-of-the-art HE-based framework Bolt (IEEE S\&P 2024) and the HE-friendly pruning method SpENCNN (ICML 2023). For ResNet-18 and Vision Transformer (ViT) on Tiny ImageNet, PrivCirNet reduces latency by 5.0× and 1.3× with iso-accuracy over Bolt, respectively, and improves accuracy by 4.1% and 12% over SpENCNN, respectively. For MobileNetV2 on ImageNet, PrivCirNet achieves 1.7× lower latency and 4.2% better accuracy over Bolt and SpENCNN, respectively. Our code and checkpoints are available on Git Hub.

# Summary. An optional shortened abstract.
summary: 

tags: [conference]
featured: true

links:
- name: Paper Link
  url: https://arxiv.org/abs/2405.14569
url_pdf: https://arxiv.org/pdf/2405.14569
url_code: https://github.com/Tianshi-Xu/PrivCirNet
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
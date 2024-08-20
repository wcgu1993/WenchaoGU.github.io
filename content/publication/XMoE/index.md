---
title: "XMoE: Sparse Models with Fine-grained and Adaptive Expert Selection"
authors:
  - Yuanhang Yang
  - Shiyi Qi
  - admin
  - Chaozheng Wang
  - Cuiyun Gao
  - Zenglin Xud

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-08-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# # Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics*
publication_short: In *ACL 2024* 

abstract: Sparse models, including sparse Mixture-of-Experts (MoE) models, have emerged as an effective approach for scaling Transformer models. However, they often suffer from computational inefficiency since a significant number of parameters are unnecessarily involved in computations by multiplying values by zero or low activation values. To address this issue, we present XMoE, a novel MoE designed to enhance both the efficacy and efficiency of sparse MoE models. XMoE leverages small experts and a threshold-based router to enable tokens to selectively engage only essential parameters. Our extensive experiments on language modeling and machine translation tasks demonstrate that enhances model performance and can decrease the computation load at MoE layers by over 50% without sacrificing performance. Furthermore, we present the versatility of by applying it to dense models, enabling sparse computation during inference. We provide a comprehensive analysis and make our code available at https://anonymous. 4open. science/r/XMoE.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Artificial Intelligence
  - Natural Language Processing

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.findings-acl.694.pdf'
url_code: 'https://github.com/ysngki/XMoE'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
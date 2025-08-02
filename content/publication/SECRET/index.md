---
title: "SECRET: Towards Scalable and Efficient Code Retrieval via Segmented Deep Hashing"
authors:
  - admin
  - Ensheng Shi
  - Yanlin Wang
  - Lun Du
  - Shi Han
  - Hongyu Zhang
  - Dongmei Zhang
  - Michael R. Lyu
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-04-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *47th IEEE/ACM International Conference on Software Engineering, 2025*
publication_short: In *ICSE2025*

abstract: Code retrieval, which retrieves code snippets based on users’ natural language descriptions, is widely used by developers and plays a pivotal role in real-world software development. The advent of deep learning has shifted the retrieval paradigm from lexical-based matching towards leveraging deep learning models to encode source code and queries into vector representations, facilitating code retrieval according to vector similarity. Despite the effectiveness of these models, managing large-scale code database presents significant challenges. Previous research proposes deep hashing-based methods, which generate hash codes for queries and code snippets and use Hamming distance for rapid recall of code candidates. However, this approach’s reliance on linear scanning of the entire code base limits its scalability. To further improve the efficiency of large-scale code retrieval, we propose a novel approach SECRET (Scalable and Efficient Code Retrieval via SegmEnTed deep hashing). SECRET converts long hash codes calculated by existing deep hashing approaches into several short hash code segments through an iterative training strategy. After training, SECRET recalls code candidates by looking up the hash tables for each segment, the time complexity of recall can thus be greatly reduced. Extensive experimental results demonstrate that SECRET can drastically reduce the retrieval time by at least 95% while achieving comparable or even higher performance of existing deep hashing approaches. Besides, SECRET also exhibits superior performance and efficiency compared to the classical hash table-based approach known as LSH under the same number of hash tables.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Artificial Intelligence
  - Software Engineering
  - Information Retrieval
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2412.11728'
url_code: ''
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
  focal_point: ""
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
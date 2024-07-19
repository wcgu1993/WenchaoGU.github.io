---
title: "CRaDLe: Deep Code Retrieval Based on Semantic Dependency
Learning"
authors:
  - admin
  - Zongjie Li
  - Cuiyun Gao
  - Chaozheng Wang
  - Hongyu Zhang
  - Zenglin Xu
  - Michael R. Lyu
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Neural Networks"
publication_short: "NN"

abstract: Code retrieval is a common practice for programmers to reuse existing code snippets in the opensource repositories. Given a user query (i.e., a natural language description), code retrieval aims at searching the most relevant ones from a set of code snippets. The main challenge of effective code retrieval lies in mitigating the semantic gap between natural language descriptions and code snippets. With the ever-increasing amount of available open-source code, recent studies resort to neural networks to learn the semantic matching relationships between the two sources. The statement-level dependency information, which highlights the dependency relations among the program statements during the execution, reflects the structural importance of one statement in the code, which is favorable for accurately capturing the code semantics but has never been explored for the code retrieval task. In this paper, we propose CRaDLe, a novel approach for Code Retrieval based on statement-level semantic Dependency Learning. Specifically, CRaDLe distills code representations through fusing both the dependency and semantic information at the statement level, and then learns a unified vector representation for each code and description pair for modeling the matching relationship. Comprehensive experiments and analysis on real-world datasets show that the proposed approach can accurately retrieve code snippets for a given query and significantly outperform the state-of-the-art approaches on the task.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Artificial Intelligence
  - Software Engineering
  - Information Retrieval
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2012.01028'
url_code: 'https://github.com/wcgu1993/CRaDLe'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
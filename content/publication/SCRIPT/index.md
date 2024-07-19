---
title: 'Source Code Summarization with Structural Relative Position Guided Transformer'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zi Gong
  - Cuiyun Gao
  - Yasheng Wang
  - admin
  - Yun Peng
  - Zenglin Xu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-03-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# # Publication name and optional abbreviated publication name.
publication: In *2022 IEEE International Conference on Software Analysis, Evolution and Reengineering*
publication_short: In *SANER 2022* 

abstract: Source code summarization aims at generating concise and clear natural language descriptions for programming languages. Well-written code summaries are beneficial for programmers to participate in the software development and maintenance process. To learn the semantic representations of
source code, recent efforts focus on incorporating the syntax structure of code into neural networks such as Transformer. Such Transformer-based approaches can better capture the long-range dependencies than other neural networks including Recurrent Neural Networks (RNNs), however, most of them do not consider the structural relative correlations between tokens, e.g., relative positions in Abstract Syntax Trees (ASTs), which is beneficial for
code semantics learning. To model the structural dependency, we propose a StruCtural RelatIve Position guided Transformer, named SCRIPT. SCRIPT first obtains the structural relative positions between tokens via parsing the ASTs of source code, and then passes them into two types of Transformer encoders. One Transformer directly adjusts the input according to the structural relative distance; and the other Transformer encodes the structural relative positions during computing the self-attention scores. Finally, we stack these two types of Transformer encoders to learn representations of source code. Experimental results show that the proposed SCRIPT outperforms the state-of-the-art methods by at least 1.6%, 1.4% and 2.8% with respect to BLEU, ROUGEL and METEOR on benchmark datasets, respectively. We further show that how the proposed SCRIPT captures the structural relative dependencies.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Artificial Intelligence
  - Software Engineering
  - Natural Language Processing

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2202.06521'
url_code: 'https://github.com/GoneZ5/SCRIPT'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

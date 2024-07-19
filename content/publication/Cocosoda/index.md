---
title: 'CoCoSoDa: Effective Contrastive Learning for Code Search'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ensheng Shi 
  - Yanlin Wang
  - admin
  - Lun Du 
  - Hongyu Zhang
  - Shi Han
  - Dongmei Zhang and
  - Hongbin Sun

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# # Publication name and optional abbreviated publication name.
publication: In *45th {IEEE/ACM} International Conference on Software Engineering*
publication_short: In *ICSE 2023* 

abstract: Code search aims to retrieve semantically relevant code snippets for a given natural language query. Recently, many approaches employing contrastive learning have shown promising results on code representation learning and greatly improved the performance of code search. However, there is still a lot of room for improvement in using contrastive learning for code search. In this paper, we propose CoCoSoDa to effectively utilize contrastive learning for code search via two key factors in contrastive learning":" data augmentation and negative samples. Specifically, soft data augmentation is to dynamically masking or replacing some tokens with their types for input sequences to generate positive samples. Momentum mechanism is used to generate large and consistent representations of negative samples in a minibatch through maintaining a queue and a momentum encoder. In addition, multimodal contrastive learning is used to pull together representations of code-query pairs and push apart the unpaired code snippets and queries. We conduct extensive experiments to evaluate the effectiveness of our approach on a large-scale dataset with six programming languages. Experimental results show that":" (1) CoCoSoDa outperforms 18 baselines and especially exceeds CodeBERT, GraphCodeBERT, and UniXcoder by 13.3%, 10.5%, and 5.9% on average MRR scores, respectively. (2) The ablation studies show the effectiveness of each component of our approach. (3) We adapt our techniques to several different pre-trained models such as RoBERTa, CodeBERT, and GraphCodeBERT and observe a significant boost in their performance in code search. (4) Our model performs robustly under different hyperparameters. Furthermore, we perform qualitative and quantitative analyses to explore reasons behind the good performance of our model.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Artificial Intelligence, Software Engineering, Information Retrieval

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10172679&casa_token=6zSs2a2pVCQAAAAA:rq1gEL_BxT9mjXTh40klbxGill1Vjv7fI-t1WjeRZ5UVMUPF9GPflhFrkjweQKOYswX2l4oc&tag=1'
url_code: 'https://github.com/DeepSoftwareAnalytics/CoCoSoDa'
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

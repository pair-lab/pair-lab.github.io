---
title: 'Contextual Transformer for Offline Meta Reinforcement Learning'
authors:
 - Runji Lin
 - Ye Li
 - Xidong Feng
 - Zhaowei Zhang
 - Xian Hong Wu Fung
 - Haifeng Zhang
 - Jun Wang
 - Yali Du
 - Yaodong Yang
date: '2022-11-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: NeurIPS 2022 Foundation Models for Decision Making Workshop

abstract: 'The pretrain-finetuning paradigm in large-scale sequence models has made significant progress in natural language processing and computer vision tasks. However, such a paradigm is still hindered by several challenges in Reinforcement Learning (RL), including the lack of self-supervised pretraining algorithms based on offline data and efficient fine-tuning/prompt-tuning over unseen downstream tasks. In this work, we explore how prompts can improve sequence modeling-based offline reinforcement learning (offline-RL) algorithms. Firstly, we propose prompt tuning for offline RL, where a context vector sequence is concatenated with the input to guide the conditional policy generation. As such, we can pretrain a model on the offline dataset with self-supervised loss and learn a prompt to guide the policy towards desired actions. Secondly, we extend our framework to Meta-RL settings and propose Contextual Meta Transformer (CMT); CMT leverages the context among different tasks as the prompt to improve generalization on unseen tasks. We conduct extensive experiments across three different offline-RL settings: offline single-agent RL on the D4RL dataset, offline Meta-RL on the MuJoCo benchmark, and offline MARL on the SMAC benchmark. Superior results validate the strong performance, and generality of our methods.'

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags: ''
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://arxiv.org/abs/2211.08016
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

---
title: 'Sequence to Sequence Reward Modeling: Improving RLHF by Language Feedback'
authors:
  - Jiayi Zhou
  - Jiaming Ji
  - Juntao Dai
  - Yaodong Yang
date: '2025-03-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: Conference paper

# Publication name and optional abbreviated publication name.
publication:  39th AAAI Conference on Artificial Intelligence (AAAI 2025)
# publication_short: IROS 2022

abstract: "Aligning the behavior of Large language models (LLMs) with human intentions and values remains a critical challenge. Reinforcement learning from human feedback (RLHF) aligns LLMs by training a reward model (RM) on human preferences and fine-tuning the LLMs to maximize RM feedback. Despite its effectiveness and popularity, RLHF is prone to biased local optimization. It means RM fails to provide feedback that accurately aligns with human preference, causing LLMs to explore unexpected generalizations, and failing to achieve alignment objectives. To mitigate this issue, we propose a novel textit sequence-to-sequence (seq2seq) reward modeling method. Its key insight is that learning from language feedback rather than scalar feedback improves RLHF without additional annotations. We replaced the reward modeling target from binary maximum likelihood estimation (MLE) with sequence MLE. This method enables richer and fine-grained language feedback without additional annotations, models, or training stages. Our experiments demonstrated its effectiveness, specifically, reducing the refusal-to-response paradigm in single-turn safety dialogues and the long-response bias in text summarization tasks. We provide further analysis that seq2seq RM improves RLHF performance across 2B and 7B LLMs on 3 NLP tasks, achieving an average win rate of 76.9%. We further show that seq2seq RM can still improve the performance of RLHF under out-of-distribution prompts."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - 
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://arxiv.org/pdf/2409.00162
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

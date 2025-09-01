---
title: 'Adaptive Pessimism via Target Q-Value for Offline Reinforcement Learning'
authors:
  - Jie Liu
  - Yinmin Zhang
  - Chuming Li
  - Yaodong Yang
  - Yu Liu
  - Wanli Ouyang
date: '2024-12-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: Journal article

# Publication name and optional abbreviated publication name.
publication:  Neural Networks
# publication_short: IROS 2022

abstract: "Offline reinforcement learning (RL) methods learn from datasets without further environment interaction, facing errors due to out-of-distribution (OOD) actions. Although effective methods have been proposed to conservatively estimate the Q-values of those OOD actions to mitigate this problem, insufficient or excessive pessimism under constant constraints often harms the policy learning process. Moreover, since the distribution of each task on the dataset varies among different environments and behavior policies, it is desirable to learn an adaptive weight for balancing constraints on the conservative estimation of Q-value and the standard RL objectives depending on each task. To achieve this, in this paper, we point out that the quantile of the Q-value is an effective metric to refer to the Q-value distribution of the fixed data set. Based on this observation, we design Adaptive Pessimism via a Target Q-value (APTQ) algorithm that balances between the pessimism constraint and the RL objective; this leads the expectation of Q-value to stably converge to a given target Q-value from a reasonable quantile of the Q-value distribution of the dataset. Experiments show that our method remarkably improves the performance of the state-of-the-art method CQL by 6.20% on the D4RL-v0 and 1.89% on the D4RL-v2."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Offline reinforcement learning
 - Representation learning
 - Machine learning
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: 
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

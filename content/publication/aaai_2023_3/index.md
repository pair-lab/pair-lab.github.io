---
title: 'Cooperative Exploration for Multi-Agent Deep Reinforcement Learning'
authors:
  - David Mguni
  - Taher Jafferjee
  - Jianhong Wang
  - Nicolas Perez-Nieves
  - Tianpei Yang
  - Matthew Taylor
  - Wenbin Song
  - Feifei Tong
  - Hui Chen
  - Jiangcheng Zhu
  - Jun Wang
  - Yaodong Yang
date: '2023-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Thirty-Seventh AAAI Conference on Artificial Intelligence
publication_short: AAAI 2023

abstract: "Reward shaping (RS) is a powerful method in reinforcement learning (RL) for overcoming the problem of sparse or uninformative rewards. However, RS typically relies on manually engineered shaping-reward functions whose construction is time-consuming and error-prone. It also requires domain knowledge which runs contrary to the goal of autonomous learning. We introduce Reinforcement Learning Optimising Shaping Algorithm (ROSA), an automated reward shaping framework in which the shaping-reward function is constructed in a Markov game between two agents. A reward-shaping agent (Shaper) uses switching controls to determine which states to add shaping rewards for more efficient learning while the other agent (Controller) learns the optimal policy for the task using these shaped rewards. We prove that ROSA, which adopts existing RL algorithms, learns to construct a shaping-reward function that is beneficial to the task thus ensuring efficient convergence to high performance policies. We demonstrate ROSA's properties in three didactic experiments and show its superior performance against state-of-the-art RS algorithms in challenging sparse reward environments."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags: ''
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://arxiv.org/abs/2103.09159
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

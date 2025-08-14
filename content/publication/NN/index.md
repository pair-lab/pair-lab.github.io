---
title: 'TIMAR: Transition-informed representation for sample-efficient multi-agent reinforcement learning'
authors:
  - Mingxiao Feng
  - Yaodong Yang
  - Wengang Zhou
  - Houqiang Li
date: '2025-04-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication:  Neural Networks
# publication_short: IROS 2022

abstract: "In MARL (Multi-Agent Reinforcement Learning), the trial-and-error learning paradigm based on multiple agents requires massive interactions to produce training samples, significantly increasing both the training cost and difficulty. Therefore, enhancing data efficiency is a core issue in MARL. However, in the context of MARL, agent partially observed information leads to a lack of consideration for agent interactions and coordination from an ego perspective under the world model, which becomes the main obstacle to improving the data efficiency of current proposed MARL methods. To address this, motivated by the success of learning a world model in RL and cognitive science, we devise a world-model-driven learning paradigm enabling agents to gain a more holistic representation of individual observation of the environment. Specifically, we present the Transition-Informed Multi-Agent Representations (TIMAR) framework, which leverages the joint transition model, i.e., a surrogate world model that captures the dynamics of the multi-agent system, to learn effective representations among agents through a self-supervised learning objective. This objective encourages consistency between predicted and actual future observations, allowing the model to learn without explicit labels. TIMAR incorporates an auxiliary module to predict future transitions based on sequential observations and actions, allowing agents to infer the latent state of the system and consider the influences of others. Unlike traditional MARL approaches that primarily focus on efficient policy improvement, TIMAR is designed to learn a useful semantic representation from high-dimensional observations. This enables the used MARL algorithm built on these representations to achieve improvements in data efficiency. Experimental evaluation of TIMAR in various MARL environments demonstrates its significantly improved performance and data efficiency compared to strong baselines such as MAPPO, HAPPO, finetuned QMIX, MAT, and MA2CL. In addition, we found TIMAR can also improve the generalization of the Transformer-based MARL algorithm such as MAT."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Multi-agent reinforcement learning
 - Self-supervised learning
 - Representation learning
 - Transformers
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

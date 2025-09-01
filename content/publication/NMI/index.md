---
title: 'Efficient and Scalable Reinforcement Learning for Large-Scale Network Control'
authors:
 - Chengdong Ma
 - Aming Li 
 - Yali Du 
 - Hao Dong
 - Yaodong Yang
date: '2024-09-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Nature Machine Intelligence
# publication_short: Neurips 2022

abstract: 'The primary challenge in the development of large-scale artificial intelligence (AI) systems lies in achieving scalable decision-making—extending the AI models while maintaining sufficient performance. Existing research indicates that distributed AI can improve scalability by decomposing complex tasks and distributing them across collaborative nodes. However, previous technologies suffered from compromised real-world applicability and scalability due to the massive requirement of communication and sampled data. Here we develop a model-based decentralized policy optimization framework, which can be efficiently deployed in multi-agent systems. By leveraging local observation through the agent-level topological decoupling of global dynamics, we prove that this decentralized mechanism achieves accurate estimations of global information. Importantly, we further introduce model learning to reinforce the optimal policy for monotonic improvement with a limited amount of sampled data. Empirical results on diverse scenarios show the superior scalability of our approach, particularly in real-world systems with hundreds of agents, thereby paving the way for scaling up AI systems.'

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Decentralized AI
 - Multi-Agent Systems
 - Model-Based AI
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://www.nature.com/articles/s42256-024-00879-7.pdf 
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

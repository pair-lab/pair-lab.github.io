---
title: 'Multi-Agent Deep Reinforcement Learning for Multi-Echelon Inventory Management'
authors:
  - Xiaotian Liu
  - Ming Hu
  - Yijie Peng
  - Yaodong Yang
date: '2024-11-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-29T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: Journal article

# Publication name and optional abbreviated publication name.
publication:  Production and Operations Management
# publication_short: IROS 2022

abstract: "We apply heterogeneous-agent proximal policy optimization (HAPPO), a multi-agent deep reinforcement learning (MADRL) algorithm, to the decentralized multi-echelon inventory management problems in both a serial supply chain and a supply chain network. We also examine whether the upfront-only information-sharing mechanism used in MADRL helps alleviate the bullwhip effect. Our results show that policies constructed by HAPPO achieve lower overall costs than policies constructed by single-agent deep reinforcement learning and other heuristic policies. Also, the application of HAPPO results in a less significant bullwhip effect than policies constructed by single-agent deep reinforcement learning where information is not shared among actors. Somewhat surprisingly, compared to using the overall costs of the system as a minimization target for each actor, HAPPO achieves lower overall costs when the minimization target for each actor is a combination of its own costs and the overall costs of the system. Our results provide a new perspective on the benefit of information sharing inside the supply chain that helps alleviate the bullwhip effect and improve the overall performance of the system. Upfront information sharing and action coordination in model training among actors is essential, with the former even more essential, for improving a supply chain’s overall performance when applying MADRL. Neither actors being fully self-interested nor actors being fully system-focused leads to the best practical performance of policies learned and constructed by MADRL. Our results also verify MADRL’s potential in solving various multi-echelon inventory management problems with complex supply chain structures and in non-stationary market environments."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - 
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://journals.sagepub.com/doi/pdf/10.1177/10591478241305863
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

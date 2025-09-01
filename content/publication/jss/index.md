---
title: 'Solving Inventory Management Problems through Deep Reinforcement Learning'
authors:
 - Qinghao Wang
 - Yijie Peng
 - Yaodong Yang
date: '2022-12-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Systems Science and Systems Engineering

abstract: 'Inventory management (e.g. lost sales) is a central problem in supply chain management. Lost sales inventory systems with lead times and complex cost function are notoriously hard to optimize. Deep reinforcement learning (DRL) methods can learn optimal decisions based on trails and errors from the environment due to its powerful complex function representation capability and has recently shown remarkable successes in solving challenging sequential decision-making problems. This paper studies typical lost sales and multi-echelon inventory systems. We first formulate inventory management problem as a Markov Decision Process by taking into account ordering cost, holding cost, fixed cost and lost-sales cost and then develop a solution framework DDLS based on Double deep Q-networks (DQN).

In the lost-sales scenario, numerical experiments demonstrate that increasing fixed ordering cost distorts the ordering behavior, while our DQN solutions with improved state space are flexible in the face of different cost parameter settings, which traditional heuristics find challenging to handle. We then study the effectiveness of our approach in multi-echelon scenarios. Empirical results demonstrate that parameter sharing can significantly improve the performance of DRL. As a form of information sharing, parameter sharing among multi-echelon suppliers promotes the collaboration of agents and improves the decision-making efficiency. Our research further demonstrates the potential of DRL in solving complex inventory management problems.'

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Reinforcement Learning
 - Supply Chain Management
 - Inventory Management
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://link.springer.com/article/10.1007/s11518-022-5544-6
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

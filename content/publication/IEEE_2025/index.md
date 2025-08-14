---
title: 'Distributed Policy Space Response Oracles in Two-Player Zero-Sum Games'
authors:
  - Hongsong Tang
  - Yingzhuo Liu
  - Letian Ni
  - Liuyu Xiang
  - Yaodong Yang
  - Ke Bi
  - Zhaofeng He
date: '2025-04-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  IEEE Transactions on Neural Networks and Learning Systems
# publication_short: IROS 2022

abstract: "Policy space response oracle (PSRO) is a population-based algorithm that can be used to solve two-player zero-sum games. In the PSRO solution framework, optimizing policy diversity is crucial for addressing nontransitive game problems, helping the agent population avoid exploitation by unfamiliar opponents. In addition, while deep reinforcement learning is highly effective in solving complex game environments, its integration with PSRO remains fragmented and lacking in effective coordination. In this study, we propose distributed PSRO to efficiently solve complex game scenarios. To enhance diversity while managing optimization costs, we introduce TOP-K truncation, which prioritizes high-quality opponents and limits the size of the policy pool during sampling. This approach not only reduces interference from less effective strategies but also ensures computational efficiency by seamlessly integrating with our distributed training framework. We also design the distributed training framework to incorporate diversity estimation directly into the sampling process, achieving diversity optimization without incurring additional computational overhead. Furthermore, we introduce the opponent first (OF) method, which enhances decision-making by leveraging opponent information during interaction sampling. We perform experimental validation using a nontransitive mixture model and AlphaStar888 to confirm the effectiveness of the TOP-K truncation approach. Finally, we demonstrate the feasibility and efficiency of the distributed training framework and the OF approach in a Google Research Football 11 versus 11 scenario."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - 
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10950104
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

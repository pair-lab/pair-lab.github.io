---
title: 'Scalable Constrained Policy Optimization for Safe Multi-agent Reinforcement Learning'
authors:
  - Lijun Zhang
  - Lin Li
  - Wei Wei
  - Huizhong Song
  - Yaodong Yang
  - Jiye Liang
date: '2025-01-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Advances in Neural Information Processing Systems 
# publication_short: IROS 2022

abstract: "A challenging problem in seeking to bring multi-agent reinforcement learning (MARL) techniques into real-world applications, such as autonomous driving and drone swarms, is how to control multiple agents safely and cooperatively to accomplish tasks. Most existing safe MARL methods learn the centralized value function by introducing a global state to guide safety cooperation. However, the global coupling arising from agents’ safety constraints and the exponential growth of the state-action space size limit their applicability in instant communication or computing resource-constrained systems and larger multi-agent systems. In this paper, we develop a novel scalable and theoretically-justified multi-agent constrained policy optimization method. This method utilizes the rigorous bounds of the trust region method and the bounds of the truncated advantage function to provide a new local policy optimization objective for each agent. Also, we prove that the safety constraints and the joint policy improvement can be met when each agent adopts a sequential update scheme to optimize a -hop policy. Then, we propose a practical algorithm called Scalable MAPPO-Lagrangian (Scal-MAPPO-L). The proposed method’s effectiveness is verified on a collection of benchmark tasks, and the results support our theory that decentralized training with local interactions can still improve reward performance and satisfy safe constraints."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - 
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://proceedings.neurips.cc/paper_files/paper/2024/file/fa76985f05e0a25c66528308dda33de0-Paper-Conference.pdf
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

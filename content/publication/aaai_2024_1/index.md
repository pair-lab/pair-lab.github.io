---
title: 'STAS: Spatial-Temporal Return Decomposition for Multi-agent Reinforcement Learning'
authors:
  - Sirui Chen
  - Zhaowei Zhang
  - Yaodong Yang
  - Yali Du
date: '2024-02-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 38th Conference on Artificial Intelligence (AAAI 2024)
# publication_short: AAAI 2023

abstract: "Centralized Training with Decentralized Execution (CTDE) has been proven to be an effective paradigm in cooperative multi-agent reinforcement learning (MARL). One of the major challenges is credit assignment, which aims to credit agents by their contributions. While prior studies have shown great success, their methods typically fail to work in episodic reinforcement learning scenarios where global rewards are revealed only at the end of the episode. They lack the functionality to model complicated relations of the delayed global reward in the temporal dimension and suffer from inefficiencies. To tackle this, we introduce Spatial-Temporal Attention with Shapley (STAS), a novel method that learns credit assignment in both temporal and spatial dimensions. It first decomposes the global return back to each time step, then utilizes the Shapley Value to redistribute the individual payoff from the decomposed global reward. To mitigate the computational complexity of the Shapley Value, we introduce an approximation of marginal contribution and utilize Monte Carlo sampling to estimate it. We evaluate our method on an Alice & Bob example and MPE environments across different scenarios. Our results demonstrate that our method effectively assigns spatial-temporal credit, outperforming all state-of-the-art baselines."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Spatial-Temporal Attention
 - Shapley Value Approximation
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://kclpure.kcl.ac.uk/ws/portalfiles/portal/241856013/stas.pdf 
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

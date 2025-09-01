---
title: 'Falcon: Fast Visuomotor Policies via Partial Denoising'
authors:
  - Haojun Chen
  - Minghao Liu
  - Chengdong Ma
  - Xiaojian Ma
  - Zailin Ma
  - Huimin Wu
  - Yuanpei Chen
  - Yifan Zhong
  - Mingzhi Wang
  - Qing Li
  - Yaodong Yang
date: '2025-03-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  International Conference on Machine Learning
publication_short: ICML 2025

abstract: "Diffusion policies are widely adopted in complex visuomotor tasks for their ability to capture multimodal action distributions. However, the multiple sampling steps required for action generation significantly harm real-time inference efficiency, which limits their applicability in real-time decision-making scenarios. Existing acceleration techniques either require retraining or degrade performance under low sampling steps. Here we propose Falcon, which mitigates this speed-performance trade-off and achieves further acceleration. The core insight is that visuomotor tasks exhibit sequential dependencies between actions. Falcon leverages this by reusing partially denoised actions from historical information rather than sampling from Gaussian noise at each step. By integrating current observations, Falcon reduces sampling steps while preserving performance. Importantly, Falcon is a training-free algorithm that can be applied as a plug-in to further improve decision efficiency on top of existing acceleration techniques. We validated Falcon in 48 simulated environments and 2 real-world robot experiments. demonstrating a 2-7x speedup with negligible performance degradation, offering a promising direction for efficient visuomotor policy design."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - 
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://openreview.net/pdf?id=fiv2M4P5vk
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

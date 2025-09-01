---
title: 'Off-Agent Trust Region Policy Optimization'
authors:
  - Ruiqing Chen
  - Xiaoyuan Zhang
  - Yali Du
  - Yifan Zhong
  - Zheng Tian
  - Fanglei Sun
  - Yaodong Yang
date: '2024-08-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: Conference paper

# Publication name and optional abbreviated publication name.
publication:  International Joint Conference on Artificial Intelligence (IJCAI 2024)
# publication_short: IROS 2022

abstract: "Leveraging the experiences of other agents offers a powerful mechanism to enhance policy optimization in multi-agent reinforcement learning (MARL). However, contemporary MARL algorithms often neglect experience sharing possibilities or adopt a simple approach via direct parameter sharing. Our work explores a refined off-agent learning framework that allows selective integration of experience from other agents to improve policy learning. Our investigation begins with a thorough assessment of current mechanisms for reusing experiences among heterogeneous agents, revealing that direct experience transfer may result in negative consequences. Moreover, even the experience of homogeneous agents requires modification before reusing. Our approach introduces off-agent adaptations to the multi-agent policy optimization methods, enabling effective and purposeful leverage of cross-agent experiences beyond conventional parameter sharing. Accompanying this, we provide a theoretical guarantee for an approximate monotonic improvement. Experiments conducted on the StarCraftII Multi-Agent Challenge (SMAC) and Google Research Football (GRF) demonstrate that our algorithms outperform state-of-the-art (SOTA) methods and achieve faster convergence, suggesting the viability of our approach for efficient experience reusing in MARL."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Experience Sharing in MARL
 - Off-Agent Learning
 - Policy Optimization
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://kclpure.kcl.ac.uk/ws/portalfiles/portal/275562544/IJCAI_24_Formatting_Instructions_2_1_.pdf 
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

---
title: 'Correlated Mean Field Imitation Learning'
authors:
  - Zhiyu Zhao
  - Ning Yang
  - Xue Yan
  - Haifeng Zhang
  - Jun Wang
  - Yaodong Yang
date: '2025-01-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication:  Autonomous Agents and Multiagent Systems
publication_short: AAMAS 2025

abstract: "We investigate multi-agent imitation learning (IL) within the framework of mean field games (MFGs), considering the presence of time-varying correlated signals. Existing MFG IL algorithms assume demonstrations are sampled from Mean Field Nash Equilibria (MFNE), limiting their adaptability to real-world scenarios. For example, in the traffic network equilibrium influenced by public routing recommendations, recommendations introduce time-varying correlated signals into the game, not captured by MFNE and other existing correlated equilibrium concepts. To address this gap, we propose Adaptive Mean Field Correlated Equilibrium (AMFCE), a general equilibrium incorporating time-varying correlated signals. We establish the existence of AMFCE under mild conditions and prove that MFNE is a subclass of AMFCE. We further propose Correlated Mean Field Imitation Learning (CMFIL), a novel IL framework designed to recover the AMFCE, accompanied by a theoretical guarantee on the quality of the recovered policy. Experimental results, including a real-world traffic flow prediction problem, demonstrate the superiority of CMFIL over state-of-the-art IL baselines, highlighting the potential of CMFIL in understanding large population behavior under correlated signals."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - 
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

---
title: 'DSR: Reinforcement Learning with Dynamical Skill Refinement'
authors:
  - Dongxiang Chen
  - Yaodong Yang
  - Ying Wen
date: '2025-01-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: Journal article

# Publication name and optional abbreviated publication name.
publication:  Frontiers of Computer Science
# publication_short: IROS 2022

abstract: "Skill-based reinforcement learning (Skill-based RL) is an efficient paradigm for solving sparse-reward tasks by extracting skills from demonstration datasets and learning high-level policy which selects skills. Because each selected skill by high-level policy is executed for multiple consecutive timesteps, the high-level policy is essentially learned in a temporally abstract Markov decision process
(TA-MDP) built on the skills, which shortens the task horizon and reduces the exploration cost. However, these skills are usually sub-optimal because of the potential low quality and low coverage of the datasets, which causes the sub-optimal performance in the downstream task. It is intuitive to refine the skills. However, it is a hard issue to refine the skills while ensuring performance improvement and avoiding non-stationarity of transition dynamics caused by skill changes. To address the dilemma of sub-optimality and ineffectiveness, we propose a unified optimization objective for the entire hierarchical policy. We theoretically prove that the unified optimization objective guarantees the performance improvement in TA-MDP, and that optimizing the performance in TA-MDP is equivalent to optimizing the performance lower bound of the entire hierarchical policy in original MDP. Furthermore, in order to overcome the phenomenon of skill space collapse, we propose the dynamical skill refinement (DSR) mechanism which names our method. The experiment results empirically validate the effectiveness of our method, and show the advantages over the state-of-the-art (SOTA) methods."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - 
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://openreview.net/pdf?id=PklYedVFUW
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

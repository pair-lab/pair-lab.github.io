---
title: 'A Game-Theoretic Framework for Managing Risk in Multi-Agent Systems'
authors:
  - Oliver Slumbers
  - David Henry Mguni
  - Stephen Marcus McAleer
  - Stefano B. Blumberg
  - Jun Wang
  - Yaodong Yang
date: '2023-04-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: The Fortieth International Conference on Machine Learning (ICML 2023)
# publication_short: ICML 2023

abstract: "In order for agents in multi-agent systems (MAS) to be safe, they need to take into account the risks posed by the actions of other agents. However, the dominant paradigm in game theory (GT) assumes that agents are not affected by risk from other agents and only strive to maximise their expected utility. For example, in hybrid human-AI driving systems, it is necessary to limit large deviations in reward resulting from car crashes. Although there are equilibrium concepts in game theory that take into account risk aversion, they either assume that agents are risk-neutral with respect to the uncertainty caused by the actions of other agents, or they are not guaranteed to exist. We introduce a new GT-based Risk-Averse Equilibrium (RAE) that always produces a solution that minimises the potential variance in reward accounting for the strategy of other agents. Theoretically and empirically, we show RAE shares many properties with a Nash Equilibrium (NE), establishing convergence properties and generalising to risk-dominant NE in certain cases. To tackle large-scale problems, we extend RAE to the PSRO multi-agent reinforcement learning (MARL) framework. We empirically demonstrate the minimum reward variance benefits of RAE in matrix games with high-risk outcomes. Results on MARL experiments show RAE generalises to risk-dominant NE in a trust dilemma game and that it reduces instances of crashing by 7x in an autonomous driving setting versus the best performing baseline."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags: ''
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://arxiv.org/abs/2205.15434
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

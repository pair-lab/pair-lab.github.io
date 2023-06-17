---
title: 'Online Double Oracle'
authors:
  - Le Cong Dinh
  - Yaodong Yang
  - Stephen McAleer
  - Zheng Tian
  - Nicolas Perez Nieves
  - Oliver Slumbers
  - David Henry Mguni
  - Haitham Bou Ammar
  - Jun Wang
date: '2022-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Transactions on Machine Learning Research (TMLR)
# publication_short: TMLR

abstract: Solving strategic games with huge action space is a critical yet under-explored topic in economics, operations research and artificial intelligence. This paper proposes new learning algorithms for solving two-player zero-sum normal-form games where the number of pure strategies is prohibitively large. Specifically, we combine no-regret analysis from online learning with Double Oracle (DO) methods from game theory. Our method -- \emph{Online Double Oracle (ODO)} -- is provably convergent to a Nash equilibrium (NE). Most importantly, unlike normal DO methods, ODO is \emph{rationale} in the sense that each agent in ODO can exploit strategic adversary with a regret bound of  where  is not the total number of pure strategies, but rather the size of \emph{effective strategy set} that is linearly dependent on the support size of the NE. On tens of different real-world games, ODO outperforms DO, PSRO methods, and no-regret algorithms such as Multiplicative Weight Update by a significant margin, both in terms of convergence rate to a NE and average payoff against strategic adversaries.

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Game Theory
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://openreview.net/pdf?id=rrMK6hYNSx
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

---
title: 'Regret-Minimizing Double Oracle for Extensive-Form Games'
authors:
  - Xiaohang Tang
  - Le Cong Dinh
  - Stephen Marcus McAleer
  - Yaodong Yang
date: '2023-04-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: The Fortieth International Conference on Machine Learning (ICML 2023)
# publication_short: ICML 2023

abstract: "By incorporating regret minimization, double oracle methods have demonstrated rapid convergence to Nash Equilibrium (NE) in normal-form games and extensive-form games, through algorithms such as online double oracle (ODO) and extensive-form double oracle (XDO), respectively. In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called Regret-Minimizing Double Oracle. Based on this framework, we extend ODO to extensive-form games and determine its sample complexity. Moreover, we demonstrate that the sample complexity of XDO can be exponential in the number of information sets |S|, owing to the exponentially decaying stopping threshold of restricted games. To solve this problem, we propose the Periodic Double Oracle (PDO) method, which has the lowest sample complexity among all existing double oracle methods, being only polynomial in |S|. Empirical evaluations on multiple poker and board games show that PDO achieves significantly faster convergence than previous double oracle algorithms and reaches a competitive level with state-of-the-art regret minimization methods."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags: ''
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://arxiv.org/abs/2304.10498
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

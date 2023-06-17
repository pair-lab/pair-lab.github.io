---
title: 'MALib: A Parallel Framework for Population-based Multi-agent Reinforcement Learning'
authors:
  - Ming Zhou
  - Ziyu Wan
  - Hanjing Wang
  - Muning Wen
  - Runzhe Wu
  - Ying Wen
  - Yaodong Yang
  - Yong Yu
  - Jun Wang
  - Weinan Zhang
date: '2023-03-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Machine Learning Research (JMLR)
# publication_short: JMLR MLOSS

abstract: "Population-based multi-agent reinforcement learning (PB-MARL) encompasses a range of methods that merge dynamic population selection with multi-agent reinforcement learning algorithms (MARL). While PB-MARL has demonstrated notable achievements in complex multi-agent tasks, its sequential execution is plagued by low computational efficiency due to the diversity in computing patterns and policy combinations. We propose a solution involving a stateless central task dispatcher and stateful workers to handle PB-MARL’s subroutines, thereby capitalizing on parallelism across various components for efficient problem-solving. In line with this approach, we introduce MALib, a parallel framework that incorporates a task control model, independent data servers, and an abstraction of MARL training paradigms. The framework has undergone extensive testing and is available under the MIT license (https://github.com/sjtu-marl/malib)."

tags:
 - Population-Based Multi-Agent Reinforcement Learning
 - Machine Learning Software

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.jmlr.org/papers/v24/22-0169.html
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [internal-project]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

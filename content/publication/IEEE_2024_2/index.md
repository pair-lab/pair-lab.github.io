---
title: 'ASP: Learn a Universal Neural Solver!'
authors:
  - Chenguang Wang
  - Zhouliang Yu
  - Stephen McAleer
  - Tianshu Yu
  - Yaodong Yang
date: '2024-01-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication:  IEEE Transactions on Pattern Analysis and Machine Intelligence
# publication_short: IJCNN 2024

abstract: "Applying machine learning to combinatorial optimization problems has the potential to improve both efficiency and accuracy. However, existing learning-based solvers often struggle with generalization when faced with changes in problem distributions and scales. In this paper, we propose a new approach called ASP: Adaptive Staircase Policy Space Response Oracle to address these generalization issues and learn a universal neural solver. ASP consists of two components: Distributional Exploration, which enhances the solver's ability to handle unknown distributions using Policy Space Response Oracles, and Persistent Scale Adaption, which improves scalability through curriculum learning. We have tested ASP on several challenging COPs, including the traveling salesman problem, the vehicle routing problem, and the prize collecting TSP, as well as the real-world instances from TSPLib and CVRPLib. Our results show that even with the same model size and weak training signal, ASP can help neural solvers explore and adapt to unseen distributions and varying scales, achieving superior performance. In particular, compared with the same neural solvers under a standard training pipeline, ASP produces a remarkable decrease in terms of the optimality gap with 90.9% and 47.43% on generated instances and real-world instances for TSP, and a decrease of 19% and 45.57% for CVRP."

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

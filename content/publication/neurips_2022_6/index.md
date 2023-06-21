---
title: 'Towards Human-Level Bimanual Dexterous Manipulation with Reinforcement Learning'
authors:
  - Yuanpei Chen
  - Tianhao Wu
  - Shengjie Wang
  - Xidong Feng
  - Jiechuang Jiang
  - Stephen Marcus McAleer
  - Hao Dong
  - Zongqing Lu
  - Song-Chun Zhu
  - Yaodong Yang
date: '2022-09-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-28T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: The 36th Conference on Neural Information Processing Systems (NeurIPS 2022) Track on Datasets and Benchmarks
# publication_short: Neurips 2022

abstract: Achieving human-level dexterity is an important open problem in robotics. However, tasks of dexterous hand manipulation even at the baby level are challenging to solve through reinforcement learning (RL). The difficulty lies in the high degrees of freedom and the required cooperation among heterogeneous agents (e.g., joints of fingers). In this study, we propose the Bimanual Dexterous Hands Benchmark (Bi-DexHands), a simulator that involves two dexterous hands with tens of bimanual manipulation tasks and thousands of target objects. Tasks in Bi-DexHands are first designed to match human-level motor skills according to literature in cognitive science, and then are built in Issac Gym; this enables highly efficient RL trainings, reaching 30,000+ FPS by only one single NVIDIA RTX 3090. We provide a comprehensive benchmark for popular RL algorithms under different settings; this includes multi-agent RL, offline RL, multi-task RL, and meta RL. Our results show that PPO type on-policy algorithms can learn to solve simple manipulation tasks that are equivalent up to 48-month human baby (e.g., catching a flying object, opening a bottle), while multi-agent RL can further help to learn manipulations that require skilled bimanual cooperation (e.g., lifting a pot, stacking blocks). Despite the success on each individual task, when it comes to mastering multiple manipulation skills, existing RL algorithms fail to work in most of the multi-task and the few-shot learning tasks, which calls for more future development from the RL community. Our project is open-sourced at https://github.com/PKU-MARL/DexterousHands.

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Robotics
 - Reinforcement Learning
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://proceedings.neurips.cc/paper_files/paper/2022/file/217a2a387f52c30755c37b0a73430291-Paper-Datasets_and_Benchmarks.pdf
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

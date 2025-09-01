---
title: 'Anyskill: Learning Open-Vocabulary Physical Skill for Interactive Agents'
authors:
  - Jieming Cui
  - Tengyu Liu
  - Nian Liu
  - Yaodong Yang
  - Yixin Zhu
  - Siyuan Huang
date: '2024-05-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-19T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: Conference paper

# Publication name and optional abbreviated publication name.
publication: Computer Vision and Pattern Recognition (CVPR 2024)
# publication_short: IROS 2022

abstract: "Traditional approaches in physics-based motion generation centered around imitation learning and reward shaping often struggle to adapt to new scenarios. To tackle this limitation we propose AnySkill a novel hierarchical method that learns physically plausible interactions following open-vocabulary instructions. Our approach begins by developing a set of atomic actions via a low-level controller trained via imitation learning. Upon receiving an open-vocabulary textual instruction AnySkill employs a high-level policy that selects and integrates these atomic actions to maximize the CLIP similarity between the agent's rendered images and the text. An important feature of our method is the use of image-based rewards for the high-level policy which allows the agent to learn interactions with objects without manual reward engineering. We demonstrate AnySkill's capability to generate realistic and natural motion sequences in response to unseen instructions of varying lengths marking it the first method capable of open-vocabulary physical skill learning for interactive humanoid agents."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Hierarchical Motion Generation
 - Open-Vocabulary Instructions
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://openaccess.thecvf.com/content/CVPR2024/papers/Cui_AnySkill_Learning_Open-Vocabulary_Physical_Skill_for_Interactive_Agents_CVPR_2024_paper.pdf 
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

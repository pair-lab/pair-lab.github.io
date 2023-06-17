---
title: 'Offline Pre-trained Multi-agent Decision Transformer'
authors:
 - Linghui Meng
 - Muning Wen
 - Chenyang Le
 - Xiyun Li
 - Dengpeng Xing
 - Weinan Zhang
 - Ying Wen
 - Haifeng Zhang
 - Jun Wang
 - Yaodong Yang
 - Bo Xu
date: '2022-06-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Machine Intelligence Research
# publication_short: Neurips 2022

abstract: 'Offline reinforcement learning leverages previously collected offline datasets to learn optimal policies with no necessity to access the real environment. Such a paradigm is also desirable for multi-agent reinforcement learning (MARL) tasks, given the combinatorially increased interactions among agents and with the environment. However, in MARL, the paradigm of offline pre-training with online fine-tuning has not been studied, nor even datasets or benchmarks for offline MARL research are available. In this paper, we facilitate the research by providing large-scale datasets and using them to examine the usage of the decision transformer in the context of MARL. We investigate the generalization of MARL offline pre-training in the following three aspects: 1) between single agents and multiple agents, 2) from offline pretraining to online fine tuning, and 3) to that of multiple downstream tasks with few-shot and zero-shot capabilities. We start by introducing the first offline MARL dataset with diverse quality levels based on the StarCraftII environment, and then propose the novel architecture of multi-agent decision transformer (MADT) for effective offline learning. MADT leverages the transformer′s modelling ability for sequence modelling and integrates it seamlessly with both offline and online MARL tasks. A significant benefit of MADT is that it learns generalizable policies that can transfer between different types of agents under different task scenarios. On the StarCraft II offline dataset, MADT outperforms the state-of-the-art offline reinforcement learning (RL) baselines, including BCQ and CQL. When applied to online tasks, the pre-trained MADT significantly improves sample efficiency and enjoys strong performance in both few-short and zero-shot cases. To the best of our knowledge, this is the first work that studies and demonstrates the effectiveness of offline pre-trained models in terms of sample efficiency and generalizability enhancements for MARL.'

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags:
 - Offline Reinforcement Learning
 - Multi-Agent Reinforcement Learning
 - Offline Multi-Agent Reinforcement Learning
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://www.mi-research.net/en/article/doi/10.1007/s11633-022-1383-7
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

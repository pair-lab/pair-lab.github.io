---
title: 'Online Markov Decision Processes with Non-oblivious Strategic Adversary'
authors:
 - Le Cong Dinh
 - David Henry Mguni
 - Long Tran-Thanh
 - Jun Wang
 - Yaodong Yang
date: '2021-10-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication:  Autonomous Agents and Multi-Agent Systems (2023)
# publication_short: JAAMAS 2023

abstract: "
We study a novel setting in Online Markov Decision Processes (OMDPs) where the loss function is chosen by a non-oblivious strategic adversary who follows a no-external regret algorithm. In this setting, we first demonstrate that MDP-Expert, an existing algorithm that works well with oblivious adversaries can still apply and achieve a policy regret bound of O(Tlog(L)−−−−−−−√+τ2Tlog(|A|)−−−−−−−−√)
 where L is the size of adversary’s pure strategy set and |A|
 denotes the size of agent’s action space.Considering real-world games where the support size of a NE is small, we further propose a new algorithm: MDP-Online Oracle Expert (MDP-OOE), that achieves a policy regret bound of O(Tlog(L)−−−−−−−√+τ2Tklog(k)−−−−−−−√)
 where k depends only on the support size of the NE. MDP-OOE leverages the key benefit of Double Oracle in game theory and thus can solve games with prohibitively large action space. Finally, to better understand the learning dynamics of no-regret methods, under the same setting of no-external regret adversary in OMDPs, we introduce an algorithm that achieves last-round convergence to a NE result. To our best knowledge, this is the first work leading to the last iteration result in OMDPs."

# Summary. An optional shortened abstract.
# summary: In this study, we further examine the theoretical convergence rate and sample complexity of such regret minimization-based double oracle methods, utilizing a unified framework called RegretMinimizing Double Oracle.

tags: ''
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://arxiv.org/pdf/2110.03604.pdf
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

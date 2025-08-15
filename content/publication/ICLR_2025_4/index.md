---
title: 'In-Context Editing: Learning Knowledge from Self-Induced Distributions'
authors:
  - Siyuan Qi
  - Bangcheng Yang
  - Kailin Jiang
  - Xiaobo Wang
  - Jiaqi Li
  - Yifan Zhong
  - Yaodong Yang
  - Zilong Zheng
date: '2024-06-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  International Conference on Learning Representations
publication_short: ICLR 2025

abstract: "In scenarios where language models must incorporate new information efficiently without extensive retraining, traditional fine-tuning methods are prone to overfitting, degraded generalization, and unnatural language generation. To address these limitations, we introduce Consistent In-Context Editing (ICE), a novel approach leveraging the model's in-context learning capability to optimize toward a contextual distribution rather than a one-hot target. ICE introduces a simple yet effective optimization framework for the model to internalize new knowledge by aligning its output distributions with and without additional context. This method enhances the robustness and effectiveness of gradient-based tuning methods, preventing overfitting and preserving the model's integrity. We analyze ICE across four critical aspects of knowledge editing: accuracy, locality, generalization, and linguistic quality, demonstrating its advantages. Experimental results confirm the effectiveness of ICE and demonstrate its potential for continual editing, ensuring that the integrity of the model is preserved while updating information."

tags:
 - Knowledge Editing
 - In-Context Learning
 - Language Models
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: https://openreview.net/pdf?id=w6rHCuN3YG
url_code: https://github.com/bigai-ai/ICE
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

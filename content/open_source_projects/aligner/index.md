---
title: 'Aligner: Achieving Efficient Alignment through Weak-to-Strong Correction'

summary: a new efficient alignment paradigm, bypasses the whole RLHF process.
abstract: "Efforts to align Large Language Models (LLMs) are mainly conducted via Reinforcement Learning from Human Feedback (RLHF) methods. However, RLHF encounters major challenges including training reward models, actor-critic engineering, and importantly, it requires access to LLM parameters. Here we introduce Aligner, a new efficient alignment paradigm that bypasses the whole RLHF process by learning the correctional residuals between the aligned and the unaligned answers. Our Aligner offers several key advantages. Firstly, it is an autoregressive seq2seq model that is trained on the query-answer-correction dataset via supervised learning; this offers a parameter-efficient alignment solution with minimal resources. Secondly, the Aligner facilitates weak-to-strong generalization; finetuning large pretrained models by Aligner's supervisory signals demonstrates strong performance boost. Thirdly, Aligner functions as a model-agnostic plug-and-play module, allowing for its direct application on different open-source and API-based models. Remarkably, Aligner-7B improves 11 different LLMs by 21.9% in helpfulness and 23.8% in harmlessness on average (GPT-4 by 17.5% and 26.9%). When finetuning (strong) Llama2-70B with (weak) Aligner-13B's supervision, we can improve Llama2 by 8.2% in helpfulness and 61.6% in harmlessness. See our dataset and code at https://aligner2024.github.io."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-02-04T13:00:00Z'
date_end: '2024-02-04T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-02-04T15:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

url_code: 'https://aligner2024.github.io/'
url_pdf: 'https://arxiv.org/pdf/2402.02416.pdf'
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---
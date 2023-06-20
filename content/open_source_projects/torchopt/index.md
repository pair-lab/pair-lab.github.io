---
title: 'TorchOpt: An Efficient PyTorch Library for Differentiable Optimization'

summary: a PyTorch-based efficient library for differentiable optimization
abstract: 'Recent years have witnessed the booming of various differentiable optimization algorithms. These algorithms exhibit different execution patterns, and their execution needs massive computational resources that go beyond a single CPU and GPU. Existing differentiable optimization libraries, however, cannot support efficient algorithm development and multi-CPU/GPU execution, making the development of differentiable optimization algorithms often cumbersome and expensive. This paper introduces TorchOpt, a PyTorch-based efficient library for differentiable optimization. TorchOpt provides a unified and expressive differentiable optimization programming abstraction. This abstraction allows users to efficiently declare and analyze various differentiable optimization programs with explicit gradients, implicit gradients, and zero-order gradients. TorchOpt further provides a high-performance distributed execution runtime. This runtime can fully parallelize computation-intensive differentiation operations (e.g. tensor tree flattening) on CPUs / GPUs and automatically distribute computation to distributed devices. Experimental results show that TorchOpt achieves 5.2× training time speedup on an 8-GPU server.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-03-18T13:00:00Z'
date_end: '2023-03-18T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-03-18T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

url_code: 'https://github.com/metaopt/torchopt/'
url_pdf: 'https://arxiv.org/pdf/2211.06934.pdf'
# url_slides: ''
# url_video: 'https://mp.weixin.qq.com/s/JTByU5vjHJlgPBscGE02QA'

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

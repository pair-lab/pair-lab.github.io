---
title: Resources
summary: Resources
date: "2023-08-25T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `assets/media/` folder).
header:
  caption: ""
  image: ""
---


## Research Advice

- [The Three Golden Rules for Successful Scientific Research](http://www.cs.utexas.edu/~EWD/ewd06xx/EWD637.PDF) (by [Prof. E.W. Dijkstra](http://www.cs.utexas.edu/~EWD/))

- [Some Modest Advice for Graduate Students](https://stearnslab.yale.edu/modest-advice) (by [Prof. Stephen C. Stearns](https://stearnslab.yale.edu/))

- [How to Write a Good Research Paper](http://spoke.compose.cs.cmu.edu/write/) (by [Prof. Mary Shaw](http://www.cs.cmu.edu/~shaw/))

- [Common Advice on Writing Research Papers](http://taoxie.cs.illinois.edu/publications/writepapers.pdf) (by [Prof. Tao Xie](http://taoxie.cs.illinois.edu/))

- [Why I gave your paper a Strong Accept](http://matt-welsh.blogspot.hk/2016/04/why-i-gave-your-paper-strong-accept.html) (by [Matt Welsh](http://www.mdw.la/))

- [Why I gave your paper a Strong Reject](http://matt-welsh.blogspot.hk/2016/04/why-i-gave-your-paper-strong-reject.html) (by [Matt Welsh](http://www.mdw.la/))

- [You and Your Research](http://www.cs.virginia.edu/~robins/YouAndYourResearch.html) (by Prof. Richard Hamming)

- [How to Give a Technical Presentation](http://homes.cs.washington.edu/~mernst/advice/giving-talk.html) (by [Prof. Michael Ernst](https://homes.cs.washington.edu/~mernst/))


- [优秀博士生和普通博士生差距能有多大？](https://www.zhihu.com/question/371659285/answer/2771642937?s_r=0&utm_campaign=shareopn&utm_medium=social&utm_oi=851431963985326080&utm_psn=1693176571161063424&utm_source=wechat_session)


> Pair-Lab课题组提供了一些可供上手的项目，并配备充足的计算资源以及实习工资；如果对下述项目感兴趣，请将你的个人简历发邮件给杨耀东老师

## 项目一：**大语言模型的安全性对齐技术**
大语言模型的巨大成功得益于基于人类反馈的强化学习（RLHF）技术，但同时也面临着一系列问题。在RLHF中，标注员对大语言模型生成的回答进行偏好性打分，通过这些打分形成偏序关系来训练模型。然而，由于人们的价值观、世界观存在差异，以及每个人所处地域文化、语言、习俗的差异，这些差异可能在标注过程中引入偏见和歧视性数据，导致依赖RLHF技术取得巨大成功的大语言模型存在潜在的安全问题。简单来说，大语言模型需要与人的价值观保持一致，并符合道德和法律层面的限制。为此，我们将探索具有约束的价值对齐技术、Moderation审查等方法，以及GPT-4 Judge等方法，以减少模型的偏见和有害性，重点关注确保大语言模型在实际应用中的安全性。加入我们的团队，你将有机会深入了解最先进的LLM工程细节和科研探索，包括但不限于以下内容：
1. **low-level** 在超大规模GPU集群上如何进行模型的并行训练、探索模型并行训练中的瓶颈和效率；
2. **high-level** 识别当前学术界和工业界开发的模型的有害性，是否在追赶GPT-3.5和GPT-4性能的同时确保了模型的安全性；考虑不同用户对象（如成年人和未成年人）时的模型安全级别以及对应的行为表现等等。

> 参考文献及阅读材料<br>
> [1] PKU-Alignment团队开源PKU-Beaver，机器之心报道：<https://mp.weixin.qq.com/s/O1RDHrmEg99zCil8ycqOGQ> <br>
> [2] PKU-Alignment 团队的github 组织：<https://github.com/PKU-Alignment>，累积stars 1500+，包括目前最受欢迎的安全强化学习基准omnisafe，第一个LLM for Safety并完全可以复现的Pipline：safe-rlhf等<br>
> [3] Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback，<https://arxiv.org/abs/2204.05862><br>
> [4] PKU-Alignment 团队开源BeaverTails，定义了safe下十四个细粒度分类，数据已开源至huggingface，论文+代码+模型即将公开，项目地址：<https://sites.google.com/view/pku-beavertails/home>


## 项目二：**基于人类反馈的强化学习方法研究**
人类反馈强化学习（Reinforcement Learning from Human Feedback, RLHF）通过人类偏好将模型与人类意图对齐，从而使得学到的模型更加符合人类的目标。我们旨在研究反馈高效的RLHF算法，即算法能够在相同数量的人类反馈数据的情况下，学到更加优异的策略。具体来说，我们会从轨迹采样机制、奖励函数/策略预训练等角度研究如何提高RLHF算法的反馈效率，降低RLHF算法在实际场景中的应用成本。此外，我们还会研究如何更加高效地将RLHF算法应用于大模型训练中，使大模型能够更加符合人类的价值观。

>参考文献：<br>
>[1] Christiano, Paul F., et al. Deep Reinforcement Learning from Human Preferences. NeurIPS 2017.<br>
>[2] Lee, Kimin, Laura Smith, and Pieter Abbeel. PEBBLE: Feedback-Efficient Interactive Reinforcement Learning via Relabeling Experience and Unsupervised Pre-training. ICML 2021.<br>
>[3] Liu, Runze, et al. Meta-Reward-Net: Implicitly Differentiable Reward Learning for Preference-based Reinforcement Learning. NeurIPS 2022.<br>
>[4] Kim, Changyeon, et al. Preference Transformer: Modeling Human Preferences using Transformers for RL. ICLR 2023.

## 项目三：**异构多智能体合作博弈求解**
异构多智能体合作博弈（Hetergeneous-Agent Cooperation）指系统中不同种类、不同角色的智能体形成有效合作、完成共同任务的科学问题，是迈向群体智能的可行途径。传统方法基于多智能体强化学习推导理论、设计算法，取得了一定的效果。近年来，大预言模型展现出令人惊叹的智能，变革NLP、CV等领域的同时也给多智能体合作问题带来了新的视角。本方向旨在提出将大模型技术与多智能体强化学习相结合的创新的解决方案，尝试探索多智能体系统的预训练问题、基于大模型的智能体之间few-shot / zero-shot合作问题、以及用多智能体合作的思想赋能大模型之间的合作对齐。具备强化学习基础、对解锁大模型智能潜力感兴趣的同学欢迎报名。

>阅读材料如下：<br>
>[1] Zhong Y, Kuba J G, Hu S, et al. Heterogeneous-Agent Reinforcement Learning[J]. arXiv preprint arXiv:2304.09870, 2023.<br>
>[2] Park J S, O'Brien J C, Cai C J, et al. Generative agents: Interactive simulacra of human behavior[J]. arXiv preprint arXiv:2304.03442, 2023.<br>
>[3] Bai Y, Kadavath S, Kundu S, et al. Constitutional AI: Harmlessness from AI Feedback[J]. arXiv preprint arXiv:2212.08073, 2022.

## 项目四：**基于交互的异构价值对齐**
价值对齐（Value Alignment）是一种赋予智能体价值观，并且使得这种价值与人类尽可能保持一致的方法，这与人类在未来能否与拥有类人甚至超人的通用人工智能体和谐共处息息相关。本方向旨在探索寻找一种让机器在拥有一种统一的基础价值观的基础之上，通过与不同文化的人类社会进行交互来实现异构价值对齐的方法。对机器学习基本概念、深度学习常用模型与技巧有一定掌握，并且对人类道德价值、人机价值对齐有研究兴趣的同学均可报名。

>阅读材料如下：<br>
>[1] Heterogeneous Value Evaluation for Large Language Models. Preprint.<br>
>[2] Using the Veil of Ignorance to align AI systems with principles of justice. PNAS 2023.<br>
>[3] Training Socially Aligned Language Models in Simulated Human Society. Preprint.

## 项目五：**价值驱动的世界模型构建**
世界模型(World Model)是一种可以模拟环境动态的模型,它可以加速智能体的学习, 帮助智能体规划。然而,学习一个高质量的世界模型本身也需要大量的数据和计算资源。本课题旨在探索一种利用事先训练好的大语言模型,为构建世界模型提供先验知识，提升泛化能力。同时我们也会探索采用此种世界模型如何帮助智能体进行规划。
我们会设计一种算法,将大语言模型中的知识迁移到世界模型中,使用它来构建环境的物理规则、对象属性以及其它先验知识以实现知识驱动。同时,我们会利用语言模型的泛化能力,实现世界模型的泛化,使之能够在新的环境中快速学习。最终,我们希望证明利用大语言模型可以有效构建高质量的世界模型,从而让强化学习智能体更快更好地学习复杂任务。对强化学习有一定基础,并且对知识驱动的基于模型的强化学习感兴趣的同学欢迎报名。

>阅读材料如下：<br>
>[1] Hao, S., Gu, Y., Ma, H., Hong, J. J., Wang, Z., Wang, D. Z., & Hu, Z. (2023). Reasoning with language model is planning with world model. arXiv preprint arXiv:2305.14992.<br>
>[2] Wang, Zizhao, et al. Causal dynamics learning for task-independent state abstraction. ICML 2023<br>
>[3] Hafner, D., Pasukonis, J., Ba, J., & Lillicrap, T. (2023). Mastering Diverse Domains through World Models. arXiv preprint arXiv:2301.04104.

## 项目六：**多智能体博弈与对齐**
博弈论（game theory）是研究决策策略和行为模式的数学理论，已经在电子游戏，机制设计等领域取得了一定的成就。近年来，大语言模型的蓬勃发展为博弈研究带来了新的机遇。本方向旨在以博弈论的视角探索大语言模型中的优化问题，包括但不限于：1.基于红蓝对抗的漏洞检测，2.大模型的鲁棒性训练及优化，3.自我博弈提升推理及规划能力等。欢迎具备一定强化学习、博弈论和大模型工程基础的同学报名。

>参考文献：<br>
>[1] Ganguli D, Lovitt L, Kernion J, et al. Red teaming language models to reduce harms: Methods, scaling behaviors, and lessons learned[J]. arXiv preprint arXiv:2209.07858, 2022.<br>
>[2] Gupta A, Lanctot M, Lazaridou A. Dynamic population-based meta-learning for multi-agent communication with natural language[J]. Advances in Neural Information Processing Systems, 2021, 34: 16899-16912.<br>
>[3] Hao S, Gu Y, Ma H, et al. Reasoning with language model is planning with world model[J]. arXiv preprint arXiv:2305.14992, 2023.

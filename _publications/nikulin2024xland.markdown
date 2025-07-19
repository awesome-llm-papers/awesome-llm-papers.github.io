---
layout: publication
title: 'Xland-100b: A Large-scale Multi-task Dataset For In-context Reinforcement
  Learning'
authors: Nikulin et al.
conference: Proceedings of the 24th international conference on Machine learning
year: 2024
bibkey: nikulin2024xland
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.08973'}]
tags: [Agentic, Tools, Evaluation, In Context Learning, ICML, Reinforcement Learning,
  Datasets, Merging]
---
Following the success of the in-context learning paradigm in large-scale
language and computer vision models, the recently emerging field of in-context
reinforcement learning is experiencing a rapid growth. However, its development
has been held back by the lack of challenging benchmarks, as all the
experiments have been carried out in simple environments and on small-scale
datasets. We present XLand-100B, a large-scale dataset for in-context
reinforcement learning based on the XLand-MiniGrid environment, as a first step
to alleviate this problem. It contains complete learning histories for nearly
\\(30,000\\) different tasks, covering \\(100\\)B transitions and 2.5B episodes. It
took 50,000 GPU hours to collect the dataset, which is beyond the reach of most
academic labs. Along with the dataset, we provide the utilities to reproduce or
expand it even further. We also benchmark common in-context RL baselines and
show that they struggle to generalize to novel and diverse tasks. With this
substantial effort, we aim to democratize research in the rapidly growing field
of in-context reinforcement learning and provide a solid foundation for further
scaling.
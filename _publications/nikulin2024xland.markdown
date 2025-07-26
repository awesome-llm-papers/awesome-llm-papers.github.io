---
layout: publication
title: 'Xland-100b: A Large-scale Multi-task Dataset For In-context Reinforcement
  Learning'
authors: Alexander Nikulin, Ilya Zisman, Alexey Zemtsov, Viacheslav Sinii, Vladislav
  Kurenkov, Sergey Kolesnikov
conference: No Venue
year: 2024
bibkey: nikulin2024xland
additional_links: [{name: Code, url: 'https://github.com/dunno-lab/xland-minigrid-datasets'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/666f1c8660142338147c0072'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.08973'}]
tags: ["Datasets", "Reinforcement Learning"]
short_authors: Nikulin et al.
---
Following the success of the in-context learning paradigm in large-scale language and computer vision models, the recently emerging field of in-context reinforcement learning is experiencing a rapid growth. However, its development has been held back by the lack of challenging benchmarks, as all the experiments have been carried out in simple environments and on small-scale datasets. We present XLand-100B, a large-scale dataset for in-context reinforcement learning based on the XLand-MiniGrid environment, as a first step to alleviate this problem. It contains complete learning histories for nearly 30,000 different tasks, covering 100B transitions and 2.5B episodes. It took 50,000 GPU hours to collect the dataset, which is beyond the reach of most academic labs. Along with the dataset, we provide the utilities to reproduce or expand it even further. With this substantial effort, we aim to democratize research in the rapidly growing field of in-context reinforcement learning and provide a solid foundation for further scaling. The code is open-source and available under Apache 2.0 licence at https://github.com/dunno-lab/xland-minigrid-datasets.

https://huggingface.co/discussions/paper/666f1c8660142338147c0072
---
layout: publication
title: 'Buffer Of Thoughts: Thought-augmented Reasoning With Large Language Models'
authors: Ling Yang, Zhaochen Yu, Tianjun Zhang, Shiyi Cao, Minkai Xu, Wentao Zhang,
  Joseph E. Gonzalez, Bin Cui
conference: No Venue
year: 2024
bibkey: yang2024buffer
additional_links: [{name: Code, url: 'https://github.com/YangLing0818/buffer-of-thought-llm'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.04271'}]
tags: ["Efficiency", "Has Code", "Prompting", "Security"]
short_authors: Yang et al.
---
We introduce Buffer of Thoughts (BoT), a novel and versatile thought-augmented reasoning approach for enhancing accuracy, efficiency and robustness of large language models (LLMs). Specifically, we propose meta-buffer to store a series of informative high-level thoughts, namely thought-template, distilled from the problem-solving processes across various tasks. Then for each problem, we retrieve a relevant thought-template and adaptively instantiate it with specific reasoning structures to conduct efficient reasoning. To guarantee the scalability and stability, we further propose buffer-manager to dynamically update the meta-buffer, thus enhancing the capacity of meta-buffer as more tasks are solved. We conduct extensive experiments on 10 challenging reasoning-intensive tasks, and achieve significant performance improvements over previous SOTA methods: 11% on Game of 24, 20% on Geometric Shapes and 51% on Checkmate-in-One. Further analysis demonstrate the superior generalization ability and model robustness of our BoT, while requiring only 12% of the cost of multi-query prompting methods (e.g., tree/graph of thoughts) on average. Notably, we find that our Llama3-8B+BoT has the potential to surpass Llama3-70B model. Our project is available at: https://github.com/YangLing0818/buffer-of-thought-llm

https://huggingface.co/discussions/paper/6662730ceaa6f8030a486e8c
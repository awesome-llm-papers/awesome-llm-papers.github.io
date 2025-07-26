---
layout: publication
title: 'Longrecipe: Recipe For Efficient Long Context Generalization In Large Languge
  Models'
authors: Zhiyuan Hu, Yuliang Liu, Jinman Zhao, Suyuchen Wang, Yan Wang, Wei Shen,
  Qing Gu, Anh Tuan Luu, See-kiong Ng, Zhiwei Jiang, Bryan Hooi
conference: No Venue
year: 2024
bibkey: hu2024longrecipe
additional_links: [{name: Code, url: 'https://github.com/zhiyuanhubj/LongRecipe)'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66d7dd21b5c8cfdee7d3805c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.00509'}]
tags: ["Efficiency", "Memory & Context"]
short_authors: Hu et al.
---
Large language models (LLMs) face significant challenges in handling long-context tasks because of their limited effective context window size during pretraining, which restricts their ability to generalize over extended sequences. Meanwhile, extending the context window in LLMs through post-pretraining is highly resource-intensive. To address this, we introduce **LongRecipe**, an efficient training strategy for extending the context window of LLMs, including impactful token analysis, position index transformation, and training optimization strategies. It simulates long-sequence inputs while maintaining training efficiency and significantly improves the model's understanding of long-range dependencies. Experiments on three types of LLMs show that LongRecipe can utilize long sequences while requiring only 30% of the target context window size, and reduces computational training resource over 85% compared to full sequence training. Furthermore, LongRecipe also preserves the original LLM's capabilities in general tasks. Ultimately, *we can extend the effective context window of open-source LLMs from 8k to 128k, achieving performance close to GPT-4 with just one day of dedicated training using a single GPU with 80G memory.* Our code is released at the [link](https://github.com/zhiyuanhubj/LongRecipe).

https://huggingface.co/discussions/paper/66d7dd21b5c8cfdee7d3805c
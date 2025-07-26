---
layout: publication
title: How To Train Data-efficient Llms
authors: Noveen Sachdeva, Benjamin Coleman, Wang-cheng Kang, Jianmo Ni, Lichan Hong,
  Ed H. Chi, James Caverlee, Julian Mcauley, Derek Zhiyuan Cheng
conference: No Venue
year: 2024
bibkey: sachdeva2024how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.09668'}]
tags: ["Training Techniques"]
short_authors: Sachdeva et al.
---
The training of large language models (LLMs) is expensive. In this paper, we study data-efficient approaches for pre-training LLMs, i.e., techniques that aim to optimize the Pareto frontier of model quality and training resource/data consumption. We seek to understand the tradeoffs associated with data selection routines based on (i) expensive-to-compute data-quality estimates, and (ii) maximization of coverage and diversity-based measures in the feature space. Our first technique, Ask-LLM, leverages the zero-shot reasoning capabilities of instruction-tuned LLMs to directly assess the quality of a training example. To target coverage, we propose Density sampling, which models the data distribution to select a diverse sample. In our comparison of 19 samplers, involving hundreds of evaluation tasks and pre-training runs, we find that Ask-LLM and Density are the best methods in their respective categories. Coverage sampling can recover the performance of the full data, while models trained on Ask-LLM data consistently outperform full-data training -- even when we reject 90% of the original dataset, while converging up to 70% faster.

https://huggingface.co/discussions/paper/65cedabea87214d107c4ea77
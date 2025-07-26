---
layout: publication
title: 'HARE: Human Priors, A Key To Small Language Model Efficiency'
authors: Lingyun Zhang, Bin Jin, Gaojian Ge, Lunhui Liu, Xuewen Shen, Mingyong Wu,
  Houqian Zhang, Yongneng Jiang, Shiqi Chen, Shi Pu
conference: No Venue
year: 2024
bibkey: zhang2024hare
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.11410'}]
tags: ["Efficiency"]
short_authors: Zhang et al.
---
Human priors play a crucial role in efficiently utilizing data in deep learning. However, with the development of large language models (LLMs), there is an increasing emphasis on scaling both model size and data volume, which often diminishes the importance of human priors in data construction. Influenced by these trends, existing Small Language Models (SLMs) mainly rely on web-scraped large-scale training data, neglecting the proper incorporation of human priors. This oversight limits the training efficiency of language models in resource-constrained settings. In this paper, we propose a principle to leverage human priors for data construction. This principle emphasizes achieving high-performance SLMs by training on a concise dataset that accommodates both semantic diversity and data quality consistency, while avoiding benchmark data leakage. Following this principle, we train an SLM named HARE-1.1B. Extensive experiments on large-scale benchmark datasets demonstrate that HARE-1.1B performs favorably against state-of-the-art SLMs, validating the effectiveness of the proposed principle. Additionally, this provides new insights into efficient language model training in resource-constrained environments from the view of human priors.

https://huggingface.co/discussions/paper/66717c111f4de3ba8b1dfbf2
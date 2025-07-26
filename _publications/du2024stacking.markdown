---
layout: publication
title: 'Stacking Your Transformers: A Closer Look At Model Growth For Efficient LLM
  Pre-training'
authors: Wenyu Du, Tongxu Luo, Zihan Qiu, Zeyu Huang, Yikang Shen, Reynold Cheng,
  Yike Guo, Jie Fu
conference: No Venue
year: 2024
bibkey: du2024stacking
additional_links: [{name: Code, url: 'https://llm-stacking.github.io/\{https://llm-stacking.github.io/\'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/665401f0f8137bb650bc1a94'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2405.15319'}]
tags: ["Training Techniques"]
short_authors: Du et al.
---
LLMs are computationally expensive to pre-train due to their large scale. Model growth emerges as a promising approach by leveraging smaller models to accelerate the training of larger ones. However, the viability of these model growth methods in efficient LLM pre-training remains underexplored. This work identifies three critical textit\{O\}bstacles: (O1) lack of comprehensive evaluation, (O2) untested viability for scaling, and (O3) lack of empirical guidelines. To tackle O1, we summarize existing approaches into four atomic growth operators and systematically evaluate them in a standardized LLM pre-training setting. Our findings reveal that a depthwise stacking operator, called G_\{stack\}, exhibits remarkable acceleration in training, leading to decreased loss and improved overall performance on eight standard NLP benchmarks compared to strong baselines. Motivated by these promising results, we conduct extensive experiments to delve deeper into G_\{stack\} to address O2 and O3. For O2 (untested scalability), our study shows that G_\{stack\} is scalable and consistently performs well, with experiments up to 7B LLMs after growth and pre-training LLMs with 750B tokens. For example, compared to a conventionally trained 7B model using 300B tokens, our G_\{stack\} model converges to the same loss with 194B tokens, resulting in a 54.6% speedup. We further address O3 (lack of empirical guidelines) by formalizing guidelines to determine growth timing and growth factor for G_\{stack\}, making it practical in general LLM pre-training. We also provide in-depth discussions and comprehensive ablation studies of G_\{stack\}. Our code and pre-trained model are available at https://llm-stacking.github.io/\{https://llm-stacking.github.io/\}.

https://huggingface.co/discussions/paper/665401f0f8137bb650bc1a94
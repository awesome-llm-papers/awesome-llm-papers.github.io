---
layout: publication
title: 'Rho-1: Not All Tokens Are What You Need'
authors: Zhenghao Lin, Zhibin Gou, Yeyun Gong, Xiao Liu, Yelong Shen, Ruochen Xu,
  Chen Lin, Yujiu Yang, Jian Jiao, Nan Duan, Weizhu Chen
conference: No Venue
year: 2024
bibkey: lin2024rho
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.07965'}]
tags: ["Datasets", "Efficiency", "Few-Shot", "Fine-Tuning", "Training Techniques"]
short_authors: Lin et al.
---
Previous language model pre-training methods have uniformly applied a next-token prediction loss to all training tokens. Challenging this norm, we posit that "Not all tokens in a corpus are equally important for language model training". Our initial analysis delves into token-level training dynamics of language model, revealing distinct loss patterns for different tokens. Leveraging these insights, we introduce a new language model called Rho-1. Unlike traditional LMs that learn to predict every next token in a corpus, Rho-1 employs Selective Language Modeling (SLM), which selectively trains on useful tokens that aligned with the desired distribution. This approach involves scoring pretraining tokens using a reference model, and then training the language model with a focused loss on tokens with higher excess loss. When continual pretraining on 15B OpenWebMath corpus, Rho-1 yields an absolute improvement in few-shot accuracy of up to 30% in 9 math tasks. After fine-tuning, Rho-1-1B and 7B achieved state-of-the-art results of 40.6% and 51.8% on MATH dataset, respectively - matching DeepSeekMath with only 3% of the pretraining tokens. Furthermore, when pretraining on 80B general tokens, Rho-1 achieves 6.8% average enhancement across 15 diverse tasks, increasing both efficiency and performance of the language model pre-training.

https://huggingface.co/discussions/paper/6618914b507806c4e6796351
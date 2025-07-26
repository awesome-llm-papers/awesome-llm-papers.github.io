---
layout: publication
title: Rethinking Diverse Human Preference Learning Through Principal Component Analysis
authors: Feng Luo, Rui Yang, Hao Sun, Chunyuan Deng, Jiarui Yao, Jingyan Shen, Huan
  Zhang, Hanjie Chen
conference: No Venue
year: 2025
bibkey: luo2025rethinking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.13131'}]
tags: ["Datasets", "Ethics & Fairness", "Reinforcement Learning", "Tools", "Training Techniques"]
short_authors: Luo et al.
---
Understanding human preferences is crucial for improving foundation models and building personalized AI systems. However, preferences are inherently diverse and complex, making it difficult for traditional reward models to capture their full range. While fine-grained preference data can help, collecting it is expensive and hard to scale. In this paper, we introduce Decomposed Reward Models (DRMs), a novel approach that extracts diverse human preferences from binary comparisons without requiring fine-grained annotations. Our key insight is to represent human preferences as vectors and analyze them using Principal Component Analysis (PCA). By constructing a dataset of embedding differences between preferred and rejected responses, DRMs identify orthogonal basis vectors that capture distinct aspects of preference. These decomposed rewards can be flexibly combined to align with different user needs, offering an interpretable and scalable alternative to traditional reward models. We demonstrate that DRMs effectively extract meaningful preference dimensions (e.g., helpfulness, safety, humor) and adapt to new users without additional training. Our results highlight DRMs as a powerful framework for personalized and interpretable LLM alignment.

https://huggingface.co/discussions/paper/67b5461f29cc269e5a4eb8bc
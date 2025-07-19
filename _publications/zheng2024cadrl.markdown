---
layout: publication
title: 'CADRL: Category-aware Dual-agent Reinforcement Learning For Explainable Recommendations
  Over Knowledge Graphs'
authors: Zheng et al.
conference: Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2024
bibkey: zheng2024cadrl
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.03166'}]
tags: [Interpretability And Explainability, Agentic, Tools, Efficiency And Optimization,
  Reinforcement Learning, SIGIR, Datasets]
---
Knowledge graphs (KGs) have been widely adopted to mitigate data sparsity and
address cold-start issues in recommender systems. While existing KGs-based
recommendation methods can predict user preferences and demands, they fall
short in generating explicit recommendation paths and lack explainability. As a
step beyond the above methods, recent advancements utilize reinforcement
learning (RL) to find suitable items for a given user via explainable
recommendation paths. However, the performance of these solutions is still
limited by the following two points. (1) Lack of ability to capture contextual
dependencies from neighboring information. (2) The excessive reliance on short
recommendation paths due to efficiency concerns. To surmount these challenges,
we propose a category-aware dual-agent reinforcement learning (CADRL) model for
explainable recommendations over KGs. Specifically, our model comprises two
components: (1) a category-aware gated graph neural network that jointly
captures context-aware item representations from neighboring entities and
categories, and (2) a dual-agent RL framework where two agents efficiently
traverse long paths to search for suitable items. Finally, experimental results
show that CADRL outperforms state-of-the-art models in terms of both
effectiveness and efficiency on large-scale datasets.
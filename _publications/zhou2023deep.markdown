---
layout: publication
title: A Deep Reinforcement Learning Approach For Interactive Search With Sentence-level
  Feedback
authors: Zhou et al.
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: zhou2023deep
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.03043'}]
tags: [Model Architecture, Fine Tuning, BERT, Agentic, EMNLP, Datasets, Reinforcement
    Learning]
---
Interactive search can provide a better experience by incorporating
interaction feedback from the users. This can significantly improve search
accuracy as it helps avoid irrelevant information and captures the users'
search intents. Existing state-of-the-art (SOTA) systems use reinforcement
learning (RL) models to incorporate the interactions but focus on item-level
feedback, ignoring the fine-grained information found in sentence-level
feedback. Yet such feedback requires extensive RL action space exploration and
large amounts of annotated data. This work addresses these challenges by
proposing a new deep Q-learning (DQ) approach, DQrank. DQrank adapts BERT-based
models, the SOTA in natural language processing, to select crucial sentences
based on users' engagement and rank the items to obtain more satisfactory
responses. We also propose two mechanisms to better explore optimal actions.
DQrank further utilizes the experience replay mechanism in DQ to store the
feedback sentences to obtain a better initial ranking performance. We validate
the effectiveness of DQrank on three search datasets. The results show that
DQRank performs at least 12% better than the previous SOTA RL approaches. We
also conduct detailed ablation studies. The ablation results demonstrate that
each model component can efficiently extract and accumulate long-term
engagement effects from the users' sentence-level feedback. This structure
offers new technologies with promised performance to construct a search system
with sentence-level interaction.
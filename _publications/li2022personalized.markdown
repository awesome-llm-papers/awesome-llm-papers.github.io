---
layout: publication
title: Personalized Prompt Learning For Explainable Recommendation
authors: Lei Li, Yongfeng Zhang, Li Chen
conference: ACM Transactions on Information Systems
year: 2023
bibkey: li2022personalized
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.07371'}]
tags: ["Model Architecture", "Prompting", "Training Techniques"]
short_authors: Lei Li, Yongfeng Zhang, Li Chen
---
Providing user-understandable explanations to justify recommendations could
help users better understand the recommended items, increase the system's ease
of use, and gain users' trust. A typical approach to realize it is natural
language generation. However, previous works mostly adopt recurrent neural
networks to meet the ends, leaving the potentially more effective pre-trained
Transformer models under-explored. In fact, user and item IDs, as important
identifiers in recommender systems, are inherently in different semantic space
as words that pre-trained models were already trained on. Thus, how to
effectively fuse IDs into such models becomes a critical issue. Inspired by
recent advancement in prompt learning, we come up with two solutions: find
alternative words to represent IDs (called discrete prompt learning), and
directly input ID vectors to a pre-trained model (termed continuous prompt
learning). In the latter case, ID vectors are randomly initialized but the
model is trained in advance on large corpora, so they are actually in different
learning stages. To bridge the gap, we further propose two training strategies:
sequential tuning and recommendation as regularization. Extensive experiments
show that our continuous prompt learning approach equipped with the training
strategies consistently outperforms strong baselines on three datasets of
explainable recommendation.
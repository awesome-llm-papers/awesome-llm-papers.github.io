---
layout: publication
title: Intent Contrastive Learning For Sequential Recommendation
authors: Yongjun Chen, Zhiwei Liu, Jia Li, Julian Mcauley, Caiming Xiong
conference: Proceedings of the ACM Web Conference 2022
year: 2022
bibkey: chen2022intent
citations: 261
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.02519'}]
tags: ["Training Techniques"]
short_authors: Chen et al.
---
Users' interactions with items are driven by various intents (e.g., preparing
for holiday gifts, shopping for fishing equipment, etc.).However, users'
underlying intents are often unobserved/latent, making it challenging to
leverage such latent intents forSequentialrecommendation(SR). To investigate
the benefits of latent intents and leverage them effectively for
recommendation, we proposeIntentContrastiveLearning(ICL), a general learning
paradigm that leverages a latent intent variable into SR. The core idea is to
learn users' intent distribution functions from unlabeled user behavior
sequences and optimize SR models with contrastive self-supervised learning
(SSL) by considering the learned intents to improve recommendation.
Specifically, we introduce a latent variable to represent users' intents and
learn the distribution function of the latent variable via clustering. We
propose to leverage the learned intents into SR models via contrastive SSL,
which maximizes the agreement between a view of sequence and its corresponding
intent. The training is alternated between intent representation learning and
the SR model optimization steps within the generalized expectation-maximization
(EM) framework. Fusing user intent information into SR also improves model
robustness. Experiments conducted on four real-world datasets demonstrate the
superiority of the proposed learning paradigm, which improves performance, and
robustness against data sparsity and noisy interaction issues.
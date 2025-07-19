---
layout: publication
title: 'Don''t Memorize; Mimic The Past: Federated Class Incremental Learning Without
  Episodic Memory'
authors: Babakniya et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: babakniya2023don
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.00497'}]
tags: [RAG, Training Techniques, Tools, CVPR, Reinforcement Learning, Datasets]
---
Deep learning models are prone to forgetting information learned in the past
when trained on new data. This problem becomes even more pronounced in the
context of federated learning (FL), where data is decentralized and subject to
independent changes for each user. Continual Learning (CL) studies this
so-called \textit\{catastrophic forgetting\} phenomenon primarily in centralized
settings, where the learner has direct access to the complete training dataset.
However, applying CL techniques to FL is not straightforward due to privacy
concerns and resource limitations. This paper presents a framework for
federated class incremental learning that utilizes a generative model to
synthesize samples from past distributions instead of storing part of past
data. Then, clients can leverage the generative model to mitigate catastrophic
forgetting locally. The generative model is trained on the server using
data-free methods at the end of each task without requesting data from clients.
Therefore, it reduces the risk of data leakage as opposed to training it on the
client's private data. We demonstrate significant improvements for the
CIFAR-100 dataset compared to existing baselines.
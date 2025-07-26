---
layout: publication
title: Learning To Select Knowledge For Response Generation In Dialog Systems
authors: Rongzhong Lian, Min Xie, Fan Wang, Jinhua Peng, Hua Wu
conference: Proceedings of the Twenty-Eighth International Joint Conference on Artificial
  Intelligence
year: 2019
bibkey: lian2019learning
citations: 185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.04911'}]
tags: ["IJCAI", "Training Techniques"]
short_authors: Lian et al.
---
End-to-end neural models for intelligent dialogue systems suffer from the
problem of generating uninformative responses. Various methods were proposed to
generate more informative responses by leveraging external knowledge. However,
few previous work has focused on selecting appropriate knowledge in the
learning process. The inappropriate selection of knowledge could prohibit the
model from learning to make full use of the knowledge. Motivated by this, we
propose an end-to-end neural model which employs a novel knowledge selection
mechanism where both prior and posterior distributions over knowledge are used
to facilitate knowledge selection. Specifically, a posterior distribution over
knowledge is inferred from both utterances and responses, and it ensures the
appropriate selection of knowledge during the training process. Meanwhile, a
prior distribution, which is inferred from utterances only, is used to
approximate the posterior distribution so that appropriate knowledge can be
selected even without responses during the inference process. Compared with the
previous work, our model can better incorporate appropriate knowledge in
response generation. Experiments on both automatic and human evaluation verify
the superiority of our model over previous baselines.
---
layout: publication
title: Mitigating Gender Bias For Neural Dialogue Generation With Adversarial Learning
authors: Haochen Liu et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
citations: 17
bibkey: liu2020mitigating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.13028'}]
tags: [Tools, Security, Ethics and Bias, Reinforcement Learning]
---
Dialogue systems play an increasingly important role in various aspects of
our daily life. It is evident from recent research that dialogue systems
trained on human conversation data are biased. In particular, they can produce
responses that reflect people's gender prejudice. Many debiasing methods have
been developed for various NLP tasks, such as word embedding. However, they are
not directly applicable to dialogue systems because they are likely to force
dialogue models to generate similar responses for different genders. This
greatly degrades the diversity of the generated responses and immensely hurts
the performance of the dialogue models. In this paper, we propose a novel
adversarial learning framework Debiased-Chat to train dialogue models free from
gender bias while keeping their performance. Extensive experiments on two
real-world conversation datasets show that our framework significantly reduces
gender bias in dialogue models while maintaining the response quality. The
implementation of the proposed framework is released.
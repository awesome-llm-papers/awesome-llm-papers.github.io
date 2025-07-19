---
layout: publication
title: Improving Image Captioning With Conditional Generative Adversarial Nets
authors: Chen et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: chen2018improving
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.07112'}]
tags: [Training Techniques, Tools, Evaluation, Model Architecture, Reinforcement Learning,
  Security, AAAI]
---
In this paper, we propose a novel
conditional-generative-adversarial-nets-based image captioning framework as an
extension of traditional reinforcement-learning (RL)-based encoder-decoder
architecture. To deal with the inconsistent evaluation problem among different
objective language metrics, we are motivated to design some "discriminator"
networks to automatically and progressively determine whether generated caption
is human described or machine generated. Two kinds of discriminator
architectures (CNN and RNN-based structures) are introduced since each has its
own advantages. The proposed algorithm is generic so that it can enhance any
existing RL-based image captioning framework and we show that the conventional
RL training method is just a special case of our approach. Empirically, we show
consistent improvements over all language evaluation metrics for different
state-of-the-art image captioning models. In addition, the well-trained
discriminators can also be viewed as objective image captioning evaluators
---
layout: publication
title: Latent Variable Model For Multi-modal Translation
authors: Iacer Calixto, Miguel Rios, Wilker Aziz
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: calixto2018latent
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.00357'}]
tags: ["Training Techniques"]
short_authors: Iacer Calixto, Miguel Rios, Wilker Aziz
---
In this work, we propose to model the interaction between visual and textual
features for multi-modal neural machine translation (MMT) through a latent
variable model. This latent variable can be seen as a multi-modal stochastic
embedding of an image and its description in a foreign language. It is used in
a target-language decoder and also to predict image features. Importantly, our
model formulation utilises visual and textual inputs during training but does
not require that images be available at test time. We show that our latent
variable MMT formulation improves considerably over strong baselines, including
a multi-task learning approach (Elliott and K\'ad\'ar, 2017) and a conditional
variational auto-encoder approach (Toyama et al., 2016). Finally, we show
improvements due to (i) predicting image features in addition to only
conditioning on them, (ii) imposing a constraint on the minimum amount of
information encoded in the latent variable, and (iii) by training on additional
target-language image descriptions (i.e. synthetic data).
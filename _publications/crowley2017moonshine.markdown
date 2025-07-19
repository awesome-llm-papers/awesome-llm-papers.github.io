---
layout: publication
title: 'Moonshine: Distilling With Cheap Convolutions'
authors: Crowley Elliot J., Gray Gavin, Storkey Amos
conference: Arxiv
year: 2017
bibkey: crowley2017moonshine
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.02613'}]
tags: [Training Techniques, Attention Mechanism, Distillation, Evaluation, Model Architecture,
  Efficiency And Optimization, Datasets]
---
Many engineers wish to deploy modern neural networks in memory-limited
settings; but the development of flexible methods for reducing memory use is in
its infancy, and there is little knowledge of the resulting cost-benefit. We
propose structural model distillation for memory reduction using a strategy
that produces a student architecture that is a simple transformation of the
teacher architecture: no redesign is needed, and the same hyperparameters can
be used. Using attention transfer, we provide Pareto curves/tables for
distillation of residual networks with four benchmark datasets, indicating the
memory versus accuracy payoff. We show that substantial memory savings are
possible with very little loss of accuracy, and confirm that distillation
provides student network performance that is better than training that student
architecture directly on data.
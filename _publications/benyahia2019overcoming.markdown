---
layout: publication
title: Overcoming Multi-model Forgetting
authors: Benyahia et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: benyahia2019overcoming
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.08232'}]
tags: [CVPR, Model Architecture, Training Techniques]
---
We identify a phenomenon, which we refer to as multi-model forgetting, that
occurs when sequentially training multiple deep networks with partially-shared
parameters; the performance of previously-trained models degrades as one
optimizes a subsequent one, due to the overwriting of shared parameters. To
overcome this, we introduce a statistically-justified weight plasticity loss
that regularizes the learning of a model's shared parameters according to their
importance for the previous models, and demonstrate its effectiveness when
training two models sequentially and for neural architecture search. Adding
weight plasticity in neural architecture search preserves the best models to
the end of the search and yields improved results in both natural language
processing and computer vision tasks.
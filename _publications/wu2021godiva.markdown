---
layout: publication
title: 'GODIVA: Generating Open-domain Videos From Natural Descriptions'
authors: Chenfei Wu, Lun Huang, Qianxi Zhang, Binyang Li, Lei Ji, Fan Yang, Guillermo
  Sapiro, Nan Duan
conference: Arxiv
year: 2021
bibkey: wu2021godiva
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.14806'}]
tags: ["Datasets", "Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Wu et al.
---
Generating videos from text is a challenging task due to its high
computational requirements for training and infinite possible answers for
evaluation. Existing works typically experiment on simple or small datasets,
where the generalization ability is quite limited. In this work, we propose
GODIVA, an open-domain text-to-video pretrained model that can generate videos
from text in an auto-regressive manner using a three-dimensional sparse
attention mechanism. We pretrain our model on Howto100M, a large-scale
text-video dataset that contains more than 136 million text-video pairs.
Experiments show that GODIVA not only can be fine-tuned on downstream video
generation tasks, but also has a good zero-shot capability on unseen texts. We
also propose a new metric called Relative Matching (RM) to automatically
evaluate the video generation quality. Several challenges are listed and
discussed as future work.
---
layout: publication
title: 'UER: An Open-source Toolkit For Pre-training Models'
authors: Zhe Zhao, Hui Chen, Jinbin Zhang, Xin Zhao, Tao Liu, Wei Lu, Xi Chen, Haotang
  Deng, Qi Ju, Xiaoyong Du
conference: 'Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP): System Demonstrations'
year: 2019
bibkey: zhao2019uer
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.05658'}]
tags: ["EMNLP", "Model Architecture", "Tools", "Training Techniques"]
short_authors: Zhao et al.
---
Existing works, including ELMO and BERT, have revealed the importance of
pre-training for NLP tasks. While there does not exist a single pre-training
model that works best in all cases, it is of necessity to develop a framework
that is able to deploy various pre-training models efficiently. For this
purpose, we propose an assemble-on-demand pre-training toolkit, namely
Universal Encoder Representations (UER). UER is loosely coupled, and
encapsulated with rich modules. By assembling modules on demand, users can
either reproduce a state-of-the-art pre-training model or develop a
pre-training model that remains unexplored. With UER, we have built a model
zoo, which contains pre-trained models based on different corpora, encoders,
and targets (objectives). With proper pre-trained models, we could achieve new
state-of-the-art results on a range of downstream datasets.
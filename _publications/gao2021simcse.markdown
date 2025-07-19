---
layout: publication
title: 'Simcse: Simple Contrastive Learning Of Sentence Embeddings'
authors: Gao Tianyu, Yao Xingcheng, Chen Danqi
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: gao2021simcse
citations: 1929
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08821'}]
tags: [RAG, EMNLP, Tools, BERT, Model Architecture, Datasets]
---
This paper presents SimCSE, a simple contrastive learning framework that
greatly advances state-of-the-art sentence embeddings. We first describe an
unsupervised approach, which takes an input sentence and predicts itself in a
contrastive objective, with only standard dropout used as noise. This simple
method works surprisingly well, performing on par with previous supervised
counterparts. We find that dropout acts as minimal data augmentation, and
removing it leads to a representation collapse. Then, we propose a supervised
approach, which incorporates annotated pairs from natural language inference
datasets into our contrastive learning framework by using "entailment" pairs as
positives and "contradiction" pairs as hard negatives. We evaluate SimCSE on
standard semantic textual similarity (STS) tasks, and our unsupervised and
supervised models using BERT base achieve an average of 76.3% and 81.6%
Spearman's correlation respectively, a 4.2% and 2.2% improvement compared to
the previous best results. We also show -- both theoretically and empirically
-- that the contrastive learning objective regularizes pre-trained embeddings'
anisotropic space to be more uniform, and it better aligns positive pairs when
supervised signals are available.
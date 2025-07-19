---
layout: publication
title: Injecting Numerical Reasoning Skills Into Knowledge Base Question Answering
  Models
authors: Feng et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2021
bibkey: feng2021injecting
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.06109'}]
tags: [Model Architecture, Tools, Training Techniques, Evaluation, ACL, Transformer,
  Datasets, Reinforcement Learning, Alt]
---
Embedding-based methods are popular for Knowledge Base Question Answering
(KBQA), but few current models have numerical reasoning skills and thus
struggle to answer ordinal constrained questions. This paper proposes a new
embedding-based KBQA framework which particularly takes numerical reasoning
into account. We present NumericalTransformer on top of NSM, a state-of-the-art
embedding-based KBQA model, to create NT-NSM. To enable better training, we
propose two pre-training tasks with explicit numerical-oriented loss functions
on two generated training datasets and a template-based data augmentation
method for enriching ordinal constrained QA dataset. Extensive experiments on
KBQA benchmarks demonstrate that with the help of our training algorithm,
NT-NSM is empowered with numerical reasoning skills and substantially
outperforms the baselines in answering ordinal constrained questions.
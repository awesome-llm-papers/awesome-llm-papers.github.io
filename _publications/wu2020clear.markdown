---
layout: publication
title: 'CLEAR: Contrastive Learning For Sentence Representation'
authors: Zhuofeng Wu, Sinong Wang, Jiatao Gu, Madian Khabsa, Fei Sun, Hao Ma
conference: Arxiv
year: 2020
bibkey: wu2020clear
citations: 229
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15466'}]
tags: ["Training Techniques"]
short_authors: Wu et al.
---
Pre-trained language models have proven their unique powers in capturing
implicit language features. However, most pre-training approaches focus on the
word-level training objective, while sentence-level objectives are rarely
studied. In this paper, we propose Contrastive LEArning for sentence
Representation (CLEAR), which employs multiple sentence-level augmentation
strategies in order to learn a noise-invariant sentence representation. These
augmentations include word and span deletion, reordering, and substitution.
Furthermore, we investigate the key reasons that make contrastive learning
effective through numerous experiments. We observe that different sentence
augmentations during pre-training lead to different performance improvements on
various downstream tasks. Our approach is shown to outperform multiple existing
methods on both SentEval and GLUE benchmarks.
---
layout: publication
title: 'CLEAR: Contrastive Learning For Sentence Representation'
authors: Zhuofeng Wu et al.
conference: Arxiv
year: 2020
citations: 228
bibkey: wu2020contrastive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15466'}]
tags: [Pre-Training, Training Techniques]
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
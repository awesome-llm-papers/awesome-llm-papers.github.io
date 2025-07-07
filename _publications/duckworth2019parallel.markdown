---
layout: publication
title: Parallel Scheduled Sampling
authors: Daniel Duckworth, Arvind Neelakantan, Ben Goodrich, Lukasz Kaiser, Samy Bengio
conference: Arxiv
year: 2019
citations: 15
bibkey: duckworth2019parallel
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.04331'}]
tags: [Training Techniques]
---
Auto-regressive models are widely used in sequence generation problems. The
output sequence is typically generated in a predetermined order, one discrete
unit (pixel or word or character) at a time. The models are trained by
teacher-forcing where ground-truth history is fed to the model as input, which
at test time is replaced by the model prediction. Scheduled Sampling aims to
mitigate this discrepancy between train and test time by randomly replacing
some discrete units in the history with the model's prediction. While
teacher-forced training works well with ML accelerators as the computation can
be parallelized across time, Scheduled Sampling involves undesirable sequential
processing. In this paper, we introduce a simple technique to parallelize
Scheduled Sampling across time. Experimentally, we find the proposed technique
leads to equivalent or better performance on image generation, summarization,
dialog generation, and translation compared to teacher-forced training. In
dialog response generation task, Parallel Scheduled Sampling achieves 1.6 BLEU
score (11.5%) improvement over teacher-forcing while in image generation it
achieves 20% and 13.8% improvement in Frechet Inception Distance (FID) and
Inception Score (IS) respectively. Further, we discuss the effects of different
hyper-parameters associated with Scheduled Sampling on the model performance.
---
layout: publication
title: On The Effect Of Dropping Layers Of Pre-trained Transformer Models
authors: Sajjad et al.
conference: Computer Speech &amp; Language
year: 2020
bibkey: sajjad2020effect
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.03844'}]
tags: [Distillation, BERT, Transformer, Model Architecture, Efficiency And Optimization,
  Pruning]
---
Transformer-based NLP models are trained using hundreds of millions or even
billions of parameters, limiting their applicability in computationally
constrained environments. While the number of parameters generally correlates
with performance, it is not clear whether the entire network is required for a
downstream task. Motivated by the recent work on pruning and distilling
pre-trained models, we explore strategies to drop layers in pre-trained models,
and observe the effect of pruning on downstream GLUE tasks. We were able to
prune BERT, RoBERTa and XLNet models up to 40%, while maintaining up to 98% of
their original performance. Additionally we show that our pruned models are on
par with those built using knowledge distillation, both in terms of size and
performance. Our experiments yield interesting observations such as, (i) the
lower layers are most critical to maintain downstream task performance, (ii)
some tasks such as paraphrase detection and sentence similarity are more robust
to the dropping of layers, and (iii) models trained using a different objective
function exhibit different learning patterns and w.r.t the layer dropping.
---
layout: publication
title: Learning Deep Transformer Models For Machine Translation
authors: Wang et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: wang2019learning
citations: 566
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01787'}]
tags: [Model Architecture, Training Techniques, Evaluation, ACL, Transformer]
---
Transformer is the state-of-the-art model in recent machine translation
evaluations. Two strands of research are promising to improve models of this
kind: the first uses wide networks (a.k.a. Transformer-Big) and has been the de
facto standard for the development of the Transformer system, and the other
uses deeper language representation but faces the difficulty arising from
learning deep networks. Here, we continue the line of research on the latter.
We claim that a truly deep Transformer model can surpass the Transformer-Big
counterpart by 1) proper use of layer normalization and 2) a novel way of
passing the combination of previous layers to the next. On WMT'16 English-
German, NIST OpenMT'12 Chinese-English and larger WMT'18 Chinese-English tasks,
our deep system (30/25-layer encoder) outperforms the shallow
Transformer-Big/Base baseline (6-layer encoder) by 0.4-2.4 BLEU points. As
another bonus, the deep model is 1.6X smaller in size and 3X faster in training
than Transformer-Big.
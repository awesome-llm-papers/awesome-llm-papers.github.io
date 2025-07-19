---
layout: publication
title: 'SCAN: Sliding Convolutional Attention Network For Scene Text Recognition'
authors: Wu et al.
conference: ACM Transactions on Multimedia Computing, Communications, and Applications
year: 2018
bibkey: wu2018scan
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.00578'}]
tags: [Interpretability And Explainability, Training Techniques, Attention Mechanism,
  Alt, Evaluation, Ethics And Bias, Model Architecture, Applications, Datasets]
---
Scene text recognition has drawn great attentions in the community of
computer vision and artificial intelligence due to its challenges and wide
applications. State-of-the-art recurrent neural networks (RNN) based models map
an input sequence to a variable length output sequence, but are usually applied
in a black box manner and lack of transparency for further improvement, and the
maintaining of the entire past hidden states prevents parallel computation in a
sequence. In this paper, we investigate the intrinsic characteristics of text
recognition, and inspired by human cognition mechanisms in reading texts, we
propose a scene text recognition method with sliding convolutional attention
network (SCAN). Similar to the eye movement during reading, the process of SCAN
can be viewed as an alternation between saccades and visual fixations. Compared
to the previous recurrent models, computations over all elements of SCAN can be
fully parallelized during training. Experimental results on several challenging
benchmarks, including the IIIT5k, SVT and ICDAR 2003/2013 datasets, demonstrate
the superiority of SCAN over state-of-the-art methods in terms of both the
model interpretability and performance.
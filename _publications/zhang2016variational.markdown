---
layout: publication
title: Variational Neural Machine Translation
authors: Biao Zhang, Deyi Xiong, Jinsong Su, Hong Duan, Min Zhang
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: zhang2016variational
citations: 198
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.07869'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Zhang et al.
---
Models of neural machine translation are often from a discriminative family
of encoderdecoders that learn a conditional distribution of a target sentence
given a source sentence. In this paper, we propose a variational model to learn
this conditional distribution for neural machine translation: a variational
encoderdecoder model that can be trained end-to-end. Different from the vanilla
encoder-decoder model that generates target translations from hidden
representations of source sentences alone, the variational model introduces a
continuous latent variable to explicitly model underlying semantics of source
sentences and to guide the generation of target translations. In order to
perform efficient posterior inference and large-scale training, we build a
neural posterior approximator conditioned on both the source and the target
sides, and equip it with a reparameterization technique to estimate the
variational lower bound. Experiments on both Chinese-English and English-
German translation tasks show that the proposed variational neural machine
translation achieves significant improvements over the vanilla neural machine
translation baselines.
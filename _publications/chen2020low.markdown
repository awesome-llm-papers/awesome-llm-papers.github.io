---
layout: publication
title: Low-resource Domain Adaptation For Compositional Task-oriented Semantic Parsing
authors: Xilun Chen, Asish Ghoshal, Yashar Mehdad, Luke Zettlemoyer, Sonal Gupta
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: chen2020low
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.03546'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Chen et al.
---
Task-oriented semantic parsing is a critical component of virtual assistants,
which is responsible for understanding the user's intents (set reminder, play
music, etc.). Recent advances in deep learning have enabled several approaches
to successfully parse more complex queries (Gupta et al., 2018; Rongali et
al.,2020), but these models require a large amount of annotated training data
to parse queries on new domains (e.g. reminder, music).
  In this paper, we focus on adapting task-oriented semantic parsers to
low-resource domains, and propose a novel method that outperforms a supervised
neural model at a 10-fold data reduction. In particular, we identify two
fundamental factors for low-resource domain adaptation: better representation
learning and better training techniques. Our representation learning uses BART
(Lewis et al., 2019) to initialize our model which outperforms encoder-only
pre-trained representations used in previous work. Furthermore, we train with
optimization-based meta-learning (Finn et al., 2017) to improve generalization
to low-resource domains. This approach significantly outperforms all baseline
methods in the experiments on a newly collected multi-domain task-oriented
semantic parsing dataset (TOPv2), which we release to the public.
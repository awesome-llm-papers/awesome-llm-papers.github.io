---
layout: publication
title: 'Bert-of-theseus: Compressing BERT By Progressive Module Replacing'
authors: Canwen Xu, Wangchunshu Zhou, Tao Ge, Furu Wei, Ming Zhou
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: xu2020bert
citations: 169
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.02925'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Xu et al.
---
In this paper, we propose a novel model compression approach to effectively
compress BERT by progressive module replacing. Our approach first divides the
original BERT into several modules and builds their compact substitutes. Then,
we randomly replace the original modules with their substitutes to train the
compact modules to mimic the behavior of the original modules. We progressively
increase the probability of replacement through the training. In this way, our
approach brings a deeper level of interaction between the original and compact
models. Compared to the previous knowledge distillation approaches for BERT
compression, our approach does not introduce any additional loss function. Our
approach outperforms existing knowledge distillation approaches on GLUE
benchmark, showing a new perspective of model compression.
---
layout: publication
title: Parameter-efficient Multi-task Fine-tuning For Transformers Via Shared Hypernetworks
authors: Rabeeh Karimi Mahabadi, Sebastian Ruder, Mostafa Dehghani, James Henderson
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: mahabadi2021parameter
citations: 115
additional_links: [{name: Code, url: 'https://github.com/rabeehk/hyperformer'}, {
    name: Paper, url: 'https://arxiv.org/abs/2106.04489'}]
tags: ["Fine-Tuning", "Model Architecture"]
short_authors: Mahabadi et al.
---
State-of-the-art parameter-efficient fine-tuning methods rely on introducing
adapter modules between the layers of a pretrained language model. However,
such modules are trained separately for each task and thus do not enable
sharing information across tasks. In this paper, we show that we can learn
adapter parameters for all layers and tasks by generating them using shared
hypernetworks, which condition on task, adapter position, and layer id in a
transformer model. This parameter-efficient multi-task learning framework
allows us to achieve the best of both worlds by sharing knowledge across tasks
via hypernetworks while enabling the model to adapt to each individual task
through task-specific adapters. Experiments on the well-known GLUE benchmark
show improved performance in multi-task learning while adding only 0.29%
parameters per task. We additionally demonstrate substantial performance
improvements in few-shot domain generalization across a variety of tasks. Our
code is publicly available in https://github.com/rabeehk/hyperformer.
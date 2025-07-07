---
layout: publication
title: 'MKD: A Multi-task Knowledge Distillation Approach For Pretrained Language
  Models'
authors: Linqing Liu, Huan Wang, Jimmy Lin, Richard Socher, Caiming Xiong
conference: Arxiv
year: 2019
citations: 19
bibkey: liu2019multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03588'}]
tags: [Distillation, Transformer, Tools, Reinforcement Learning, BERT, Efficiency
    and Optimization, Model Architecture]
---
Pretrained language models have led to significant performance gains in many
NLP tasks. However, the intensive computing resources to train such models
remain an issue. Knowledge distillation alleviates this problem by learning a
light-weight student model. So far the distillation approaches are all
task-specific. In this paper, we explore knowledge distillation under the
multi-task learning setting. The student is jointly distilled across different
tasks. It acquires more general representation capacity through multi-tasking
distillation and can be further fine-tuned to improve the model in the target
domain. Unlike other BERT distillation methods which specifically designed for
Transformer-based architectures, we provide a general learning framework. Our
approach is model agnostic and can be easily applied on different future
teacher model architectures. We evaluate our approach on a Transformer-based
and LSTM based student model. Compared to a strong, similarly LSTM-based
approach, we achieve better quality under the same computational constraints.
Compared to the present state of the art, we reach comparable results with much
faster inference speed.
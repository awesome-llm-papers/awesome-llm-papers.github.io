---
layout: publication
title: Structured Pruning Learns Compact And Accurate Models
authors: Mengzhou Xia, Zexuan Zhong, Danqi Chen
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: xia2022structured
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.00408'}]
tags: ["Efficiency"]
short_authors: Mengzhou Xia, Zexuan Zhong, Danqi Chen
---
The growing size of neural language models has led to increased attention in
model compression. The two predominant approaches are pruning, which gradually
removes weights from a pre-trained model, and distillation, which trains a
smaller compact model to match a larger one. Pruning methods can significantly
reduce the model size but hardly achieve large speedups as distillation.
However, distillation methods require large amounts of unlabeled data and are
expensive to train. In this work, we propose a task-specific structured pruning
method CoFi (Coarse- and Fine-grained Pruning), which delivers highly
parallelizable subnetworks and matches the distillation methods in both
accuracy and latency, without resorting to any unlabeled data. Our key insight
is to jointly prune coarse-grained (e.g., layers) and fine-grained (e.g., heads
and hidden units) modules, which controls the pruning decision of each
parameter with masks of different granularity. We also devise a layerwise
distillation strategy to transfer knowledge from unpruned to pruned models
during optimization. Our experiments on GLUE and SQuAD datasets show that CoFi
yields models with over 10x speedups with a small accuracy drop, showing its
effectiveness and efficiency compared to previous pruning and distillation
approaches.
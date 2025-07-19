---
layout: publication
title: Lightweight And Post-training Structured Pruning For On-device Large Lanaguage
  Models
authors: Xu et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2025
bibkey: xu2025lightweight
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.15255'}]
tags: [Training Techniques, EMNLP, Efficiency And Optimization, Applications, Fine
    Tuning, Pruning]
---
Considering the hardware-friendly characteristics and broad applicability,
structured pruning has emerged as an efficient solution to reduce the resource
demands of large language models (LLMs) on resource-constrained devices.
Traditional structured pruning methods often need fine-tuning to recover
performance loss, which incurs high memory overhead and substantial data
requirements, rendering them unsuitable for on-device applications.
Additionally, post-training structured pruning techniques typically necessitate
specific activation functions or architectural modifications, thereby limiting
their scope of applications. Herein, we introduce COMP, a lightweight
post-training structured pruning method that employs a hybrid-granularity
pruning strategy. COMP initially prunes selected model layers based on their
importance at a coarse granularity, followed by fine-grained neuron pruning
within the dense layers of each remaining model layer. To more accurately
evaluate neuron importance, COMP introduces a new matrix condition-based
metric. Subsequently, COMP utilizes mask tuning to recover accuracy without the
need for fine-tuning, significantly reducing memory consumption. Experimental
results demonstrate that COMP improves performance by 6.13% on the LLaMA-2-7B
model with a 20% pruning ratio compared to LLM-Pruner, while simultaneously
reducing memory overhead by 80%.
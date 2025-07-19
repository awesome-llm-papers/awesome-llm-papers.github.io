---
layout: publication
title: Memory Layers At Scale
authors: Berges et al.
conference: Journal of Climate
year: 2024
bibkey: berges2024memory
citations: 159
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.09764'}]
tags: [Scaling Laws, Efficiency And Optimization, Large Scale Training]
---
Memory layers use a trainable key-value lookup mechanism to add extra
parameters to a model without increasing FLOPs. Conceptually, sparsely
activated memory layers complement compute-heavy dense feed-forward layers,
providing dedicated capacity to store and retrieve information cheaply. This
work takes memory layers beyond proof-of-concept, proving their utility at
contemporary scale. On downstream tasks, language models augmented with our
improved memory layer outperform dense models with more than twice the
computation budget, as well as mixture-of-expert models when matched for both
compute and parameters. We find gains are especially pronounced for factual
tasks. We provide a fully parallelizable memory layer implementation,
demonstrating scaling laws with up to 128B memory parameters, pretrained to 1
trillion tokens, comparing to base models with up to 8B parameters.
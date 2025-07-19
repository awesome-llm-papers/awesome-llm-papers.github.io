---
layout: publication
title: 'Open-magvit2: An Open-source Project Toward Democratizing Auto-regressive
  Visual Generation'
authors: Luo et al.
conference: Media, Culture &amp; Society
year: 2024
bibkey: luo2024open
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.04410'}]
tags: [Evaluation, Datasets]
---
The Open-MAGVIT2 project produces an open-source replication of Google's
MAGVIT-v2 tokenizer, a tokenizer with a super-large codebook (i.e., \\(2^\{18\}\\)
codes), and achieves the state-of-the-art reconstruction performance on
ImageNet and UCF benchmarks. We also provide a tokenizer pre-trained on
large-scale data, significantly outperforming Cosmos on zero-shot benchmarks
(1.93 vs. 0.78 rFID on ImageNet original resolution). Furthermore, we explore
its application in plain auto-regressive models to validate scalability
properties, producing a family of auto-regressive image generation models
ranging from 300M to 1.5B. To assist auto-regressive models in predicting with
a super-large vocabulary, we factorize it into two sub-vocabulary of different
sizes by asymmetric token factorization, and further introduce ``next sub-token
prediction'' to enhance sub-token interaction for better generation quality. We
release all models and codes to foster innovation and creativity in the field
of auto-regressive visual generation.
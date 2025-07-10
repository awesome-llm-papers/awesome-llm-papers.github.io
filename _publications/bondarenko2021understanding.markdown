---
layout: publication
title: Understanding And Overcoming The Challenges Of Efficient Transformer Quantization
authors: Yelysei Bondarenko, Markus Nagel, Tijmen Blankevoort
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
citations: 35
bibkey: bondarenko2021understanding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.12948'}, {name: Code,
    url: 'https://github.com/qualcomm-ai-research/transformer-quantization'}]
tags: [Has Code, Model Architecture, Attention Mechanism, Transformer, RAG, Quantization,
  BERT, Efficiency and Optimization, Training Techniques, Evaluation]
---
Transformer-based architectures have become the de-facto standard models for
a wide range of Natural Language Processing tasks. However, their memory
footprint and high latency are prohibitive for efficient deployment and
inference on resource-limited devices. In this work, we explore quantization
for transformers. We show that transformers have unique quantization challenges
-- namely, high dynamic activation ranges that are difficult to represent with
a low bit fixed-point format. We establish that these activations contain
structured outliers in the residual connections that encourage specific
attention patterns, such as attending to the special separator token. To combat
these challenges, we present three solutions based on post-training
quantization and quantization-aware training, each with a different set of
compromises for accuracy, model size, and ease of use. In particular, we
introduce a novel quantization scheme -- per-embedding-group quantization. We
demonstrate the effectiveness of our methods on the GLUE benchmark using BERT,
establishing state-of-the-art results for post-training quantization. Finally,
we show that transformer weights and embeddings can be quantized to ultra-low
bit-widths, leading to significant memory savings with a minimum accuracy loss.
Our source code is available
at~https://github.com/qualcomm-ai-research/transformer-quantization.
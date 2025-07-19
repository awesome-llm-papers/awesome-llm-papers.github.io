---
layout: publication
title: 'Similarity-aware Token Pruning: Your VLM But Faster'
authors: Jeddi et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: jeddi2025similarity
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.11549'}]
tags: [RAG, Training Techniques, Attention Mechanism, Tools, Evaluation, Transformer,
  Model Architecture, Efficiency And Optimization, Reinforcement Learning, Multimodal
    Models, Pruning, Datasets]
---
The computational demands of Vision Transformers (ViTs) and Vision-Language
Models (VLMs) remain a significant challenge due to the quadratic complexity of
self-attention. While token pruning offers a promising solution, existing
methods often introduce training overhead or fail to adapt dynamically across
layers. We present SAINT, a training-free token pruning framework that
leverages token similarity and a graph-based formulation to dynamically
optimize pruning rates and redundancy thresholds. Through systematic analysis,
we identify a universal three-stage token evolution process
(aligner-explorer-aggregator) in transformers, enabling aggressive pruning in
early stages without sacrificing critical information. For ViTs, SAINT doubles
the throughput of ViT-H/14 at 224px with only 0.6% accuracy loss on
ImageNet-1K, surpassing the closest competitor by 0.8%. For VLMs, we apply
SAINT in three modes: ViT-only, LLM-only, and hybrid. SAINT reduces LLaVA-13B's
tokens by 75%, achieving latency comparable to LLaVA-7B with less than 1%
performance loss across benchmarks. Our work establishes a unified, practical
framework for efficient inference in ViTs and VLMs.
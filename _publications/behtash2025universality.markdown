---
layout: publication
title: Universality Of Layer-level Entropy-weighted Quantization Beyond Model Architecture
  And Size
authors: Behtash et al.
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: behtash2025universality
citations: 170
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.04704'}]
tags: [RAG, Tools, CVPR, Transformer, Model Architecture, Efficiency And Optimization,
  Quantization]
---
We present a novel approach to selective model quantization that transcends
the limitations of architecture-specific and size-dependent compression methods
for Large Language Models (LLMs) using Entropy-Weighted Quantization (EWQ). By
analyzing the entropy distribution across transformer blocks, EWQ determines
which blocks can be safely quantized without causing significant performance
degradation, independent of model architecture or size. Our method outperforms
uniform quantization approaches, maintaining Massive Multitask Language
Understanding (MMLU) accuracy scores within 0.5% of unquantized models while
reducing memory usage by up to 18%. We demonstrate the effectiveness of EWQ
across multiple architectures -- from 1.6B to 70B parameters -- and showcase
consistent improvements in the quality-compression trade-off regardless of
model scale or architectural design. A surprising finding of EWQ is its ability
to reduce perplexity compared to unquantized models, suggesting the presence of
beneficial regularization through selective precision reduction. This
improvement holds across different model families, indicating a fundamental
relationship between layer-level entropy and optimal precision requirements.
Additionally, we introduce FastEWQ, a rapid method for entropy distribution
analysis that eliminates the need for loading model weights. This technique
leverages universal characteristics of entropy distribution that persist across
various architectures and scales, enabling near-instantaneous quantization
decisions while maintaining 80% classification accuracy with full entropy
analysis. Our results demonstrate that effective quantization strategies can be
developed independently of specific architectural choices or model sizes,
opening new possibilities for efficient LLM deployment.
---
layout: publication
title: Hyper Compressed Fine-tuning Of Large Foundation Models With Quantum Inspired
  Adapters
authors: Raj Snehal, Coyle Brian
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: raj2025hyper
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.06916'}]
tags: [RAG, EMNLP, Training Techniques, Evaluation, Transformer, Model Architecture,
  Fine Tuning, Datasets]
---
Fine-tuning pre-trained large foundation models for specific tasks has become
increasingly challenging due to the computational and storage demands
associated with full parameter updates. Parameter-Efficient Fine-Tuning (PEFT)
methods address this issue by updating only a small subset of model parameters
using adapter modules. In this work, we propose *Quantum-Inspired
Adapters*, a PEFT approach inspired by Hamming-weight preserving quantum
circuits from quantum machine learning literature. These models can be both
expressive and parameter-efficient by operating in a combinatorially large
space while simultaneously preserving orthogonality in weight parameters. We
test our proposed adapters by adapting large language models and large vision
transformers on benchmark datasets. Our method can achieve 99.2% of the
performance of existing fine-tuning methods such LoRA with a 44x parameter
compression on language understanding datasets like GLUE and VTAB. Compared to
existing orthogonal fine-tuning methods such as OFT or BOFT, we achieve 98%
relative performance with 25x fewer parameters. This demonstrates competitive
performance paired with a significant reduction in trainable parameters.
Through ablation studies, we determine that combining multiple Hamming-weight
orders with orthogonality and matrix compounding are essential for performant
fine-tuning. Our findings suggest that Quantum-Inspired Adapters offer a
promising direction for efficient adaptation of language and vision models in
resource-constrained environments.
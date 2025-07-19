---
layout: publication
title: Sequence Length Scaling In Vision Transformers For Scientific Images On Frontier
authors: Tsaris et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: tsaris2024sequence
citations: 478
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.15780'}]
tags: [RAG, Training Techniques, Attention Mechanism, CVPR, Transformer, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning, Applications, Fine Tuning]
---
Vision Transformers (ViTs) are pivotal for foundational models in scientific
imagery, including Earth science applications, due to their capability to
process large sequence lengths. While transformers for text has inspired
scaling sequence lengths in ViTs, yet adapting these for ViTs introduces unique
challenges. We develop distributed sequence parallelism for ViTs, enabling them
to handle up to 1M tokens. Our approach, leveraging DeepSpeed-Ulysses and
Long-Sequence-Segmentation with model sharding, is the first to apply sequence
parallelism in ViT training, achieving a 94% batch scaling efficiency on 2,048
AMD-MI250X GPUs. Evaluating sequence parallelism in ViTs, particularly in
models up to 10B parameters, highlighted substantial bottlenecks. We countered
these with hybrid sequence, pipeline, tensor parallelism, and flash attention
strategies, to scale beyond single GPU memory limits. Our method significantly
enhances climate modeling accuracy by 20% in temperature predictions, marking
the first training of a transformer model on a full-attention matrix over 188K
sequence length.
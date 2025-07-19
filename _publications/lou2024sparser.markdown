---
layout: publication
title: 'Sparser Is Faster And Less Is More: Efficient Sparse Attention For Long-range
  Transformers'
authors: Lou et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: lou2024sparser
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.16747'}]
tags: [Training Techniques, Attention Mechanism, GPT, Transformer, Model Architecture,
  Efficiency And Optimization, Language Modeling, Reinforcement Learning, Applications,
  Fine Tuning, AAAI, TACL]
---
Accommodating long sequences efficiently in autoregressive Transformers,
especially within an extended context window, poses significant challenges due
to the quadratic computational complexity and substantial KV memory
requirements inherent in self-attention mechanisms. In this work, we introduce
SPARSEK Attention, a novel sparse attention mechanism designed to overcome
these computational and memory obstacles while maintaining performance. Our
approach integrates a scoring network and a differentiable top-k mask operator,
SPARSEK, to select a constant number of KV pairs for each query, thereby
enabling gradient-based optimization. As a result, SPARSEK Attention offers
linear time complexity and constant memory footprint during generation.
Experimental results reveal that SPARSEK Attention outperforms previous sparse
attention methods and provides significant speed improvements during both
training and inference, particularly in language modeling and downstream tasks.
Furthermore, our method can be seamlessly integrated into pre-trained Large
Language Models (LLMs) with minimal fine-tuning, offering a practical solution
for effectively managing long-range dependencies in diverse applications.
---
layout: publication
title: Self-attention Limits Working Memory Capacity Of Transformer-based Models
authors: Gong Dongyu, Zhang Hantao
conference: Psychological Science
year: 2024
bibkey: gong2024self
citations: 144
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.10715'}]
tags: [Interpretability And Explainability, Training Techniques, Attention Mechanism,
  Transformer, Model Architecture]
---
Recent work on Transformer-based large language models (LLMs) has revealed
striking limits in their working memory capacity, similar to what has been
found in human behavioral studies. Specifically, these models' performance
drops significantly on N-back tasks as N increases. However, there is still a
lack of mechanistic interpretability as to why this phenomenon would arise.
Inspired by the executive attention theory from behavioral sciences, we
hypothesize that the self-attention mechanism within Transformer-based models
might be responsible for their working memory capacity limits. To test this
hypothesis, we train vanilla decoder-only transformers to perform N-back tasks
and find that attention scores gradually aggregate to the N-back positions over
training, suggesting that the model masters the task by learning a strategy to
pay attention to the relationship between the current position and the N-back
position. Critically, we find that the total entropy of the attention score
matrix increases as N increases, suggesting that the dispersion of attention
scores might be the cause of the capacity limit observed in N-back tasks. Our
findings thus offer insights into the shared role of attention in both human
and artificial intelligence. Moreover, the limitations of the self-attention
mechanism revealed in the current study could inform future efforts to design
more powerful model architectures with enhanced working memory capacity and
cognitive capabilities.
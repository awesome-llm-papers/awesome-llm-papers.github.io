---
layout: publication
title: Mistral 7B
authors: Albert et al.
conference: Arxiv
year: 2023
bibkey: albert2023mistral
citations: 149
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2310.06825v1'}]
tags: [RAG, Attention Mechanism, Evaluation, Model Architecture, Efficiency And Optimization,
  Datasets, LLM For Code]
---
We introduce Mistral 7B v0.1, a 7-billion-parameter language model engineered
for superior performance and efficiency. Mistral 7B outperforms Llama 2 13B
across all evaluated benchmarks, and Llama 1 34B in reasoning, mathematics, and
code generation. Our model leverages grouped-query attention (GQA) for faster
inference, coupled with sliding window attention (SWA) to effectively handle
sequences of arbitrary length with a reduced inference cost. We also provide a
model fine-tuned to follow instructions, Mistral 7B -- Instruct, that surpasses
the Llama 2 13B -- Chat model both on human and automated benchmarks. Our
models are released under the Apache 2.0 license.
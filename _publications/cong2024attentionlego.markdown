---
layout: publication
title: 'Attentionlego: An Open-source Building Block For Spatially-scalable Large
  Language Model Accelerator With Processing-in-memory Technology'
authors: Cong et al.
conference: ACM SIGARCH Computer Architecture News
year: 2024
bibkey: cong2024attentionlego
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.11459'}]
tags: [Attention Mechanism, Agentic, Transformer, Model Architecture, Multimodal Models]
---
Large language models (LLMs) with Transformer architectures have become
phenomenal in natural language processing, multimodal generative artificial
intelligence, and agent-oriented artificial intelligence. The self-attention
module is the most dominating sub-structure inside Transformer-based LLMs.
Computation using general-purpose graphics processing units (GPUs) inflicts
reckless demand for I/O bandwidth for transferring intermediate calculation
results between memories and processing units. To tackle this challenge, this
work develops a fully customized vanilla self-attention accelerator,
AttentionLego, as the basic building block for constructing spatially
expandable LLM processors. AttentionLego provides basic implementation with
fully-customized digital logic incorporating Processing-In-Memory (PIM)
technology. It is based on PIM-based matrix-vector multiplication and look-up
table-based Softmax design. The open-source code is available online:
https://bonany.cc/attentionleg.
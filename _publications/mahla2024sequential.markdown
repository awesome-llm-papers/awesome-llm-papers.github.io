---
layout: publication
title: Sequential Compression Layers For Efficient Federated Learning In Foundational
  Models
authors: Mahla Navyansh, Gupta Sunny, Sethi Amit
conference: IEEE Transactions on Neural Networks and Learning Systems
year: 2024
bibkey: mahla2024sequential
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.07021'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  Fine Tuning]
---
Federated Learning (FL) has gained popularity for fine-tuning large language
models (LLMs) across multiple nodes, each with its own private data. While LoRA
has been widely adopted for parameter efficient federated fine-tuning, recent
theoretical and empirical studies highlight its suboptimal performance in the
federated learning context. In response, we propose a novel, simple, and more
effective parameter-efficient fine-tuning method that does not rely on LoRA.
Our approach introduces a small multi-layer perceptron (MLP) layer between two
existing MLP layers the up proj (the FFN projection layer following the
self-attention module) and down proj within the feed forward network of the
transformer block. This solution addresses the bottlenecks associated with LoRA
in federated fine tuning and outperforms recent LoRA-based approaches,
demonstrating superior performance for both language models and vision
encoders.
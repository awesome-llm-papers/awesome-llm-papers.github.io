---
layout: publication
title: '1bit-merging: Dynamic Quantized Merging For Large Language Models'
authors: Liu et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: liu20251bit
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.10743'}]
tags: [RAG, Attention Mechanism, Tools, Model Architecture, Efficiency And Optimization,
  Merging, LLM For Code]
---
Recent advances in large language models have led to specialized models excelling in specific domains, creating a need for efficient model merging techniques. While traditional merging approaches combine parameters into a single static model, they often compromise task-specific performance. However, task-specific routing methods maintain accuracy but introduce substantial storage overhead. We present \texttt\{1bit\}-Merging, a novel framework that integrates task-specific routing with 1-bit quantized task vectors to balance performance and storage efficiency. Our approach leverages the observation that different task-specific models store knowledge in distinct layers-chat models primarily in attention layers and math/code models in MLP layers, enabling targeted compression strategies. Through extensive experiments with LLaMA2 and Mistral model families across chat, mathematical reasoning, and code generation tasks, we demonstrate that 1bit-Merging achieves comparable or superior performance to existing methods while significantly reducing storage requirements. Our framework offers a practical solution for combining specialized models while maintaining their individual strengths and addressing the storage challenges of current approaches.
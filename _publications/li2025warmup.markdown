---
layout: publication
title: 'Warmup Generations: A Task-agnostic Approach For Guiding Sequence-to-sequence
  Learning With Unsupervised Initial State Generation'
authors: Li et al.
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: li2025warmup
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.12304'}]
tags: [Interpretability And Explainability, Training Techniques, Efficiency And Optimization,
  Tools, Fine Tuning, Agentic, EMNLP, Reinforcement Learning]
---
Traditional supervised fine-tuning (SFT) strategies for sequence-to-sequence
tasks often train models to directly generate the target output. Recent work
has shown that guiding models with intermediate steps, such as keywords,
outlines, or reasoning chains, can significantly improve performance,
coherence, and interpretability. However, these methods often depend on
predefined intermediate formats and annotated data, limiting their scalability
and generalizability. In this work, we introduce a task-agnostic framework that
enables models to generate intermediate "warmup" sequences. These warmup
sequences, serving as an initial state for subsequent generation, are optimized
to enhance the probability of generating the target sequence without relying on
external supervision or human-designed structures. Drawing inspiration from
reinforcement learning principles, our method iteratively refines these
intermediate steps to maximize their contribution to the final output, similar
to reward-driven optimization in reinforcement learning with human feedback.
Experimental results across tasks such as translation, summarization, and
multi-choice question answering for logical reasoning show that our approach
outperforms traditional SFT methods, and offers a scalable and flexible
solution for sequence-to-sequence tasks.
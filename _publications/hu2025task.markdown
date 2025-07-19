---
layout: publication
title: Task-aware Parameter-efficient Fine-tuning Of Large Pre-trained Models At The
  Edge
authors: Hu et al.
conference: Nature Machine Intelligence
year: 2025
bibkey: hu2025task
citations: 417
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.03718'}]
tags: [Tools, Training Techniques, Fine Tuning, LLM for Code, RAG]
---
Large language models (LLMs) have achieved remarkable success in various
tasks, such as decision-making, reasoning, and question answering. They have
been widely used in edge devices. However, fine-tuning LLMs to specific tasks
at the edge is challenging due to the high computational cost and the limited
storage and energy resources at the edge. To address this issue, we propose
TaskEdge, a task-aware parameter-efficient fine-tuning framework at the edge,
which allocates the most effective parameters to the target task and only
updates the task-specific parameters. Specifically, we first design a parameter
importance calculation criterion that incorporates both weights and input
activations into the computation of weight importance. Then, we propose a
model-agnostic task-specific parameter allocation algorithm to ensure that
task-specific parameters are distributed evenly across the model, rather than
being concentrated in specific regions. In doing so, TaskEdge can significantly
reduce the computational cost and memory usage while maintaining performance on
the target downstream tasks by updating less than 0.1% of the parameters. In
addition, TaskEdge can be easily integrated with structured sparsity to enable
acceleration by NVIDIA's specialized sparse tensor cores, and it can be
seamlessly integrated with LoRA to enable efficient sparse low-rank adaptation.
Extensive experiments on various tasks demonstrate the effectiveness of
TaskEdge.
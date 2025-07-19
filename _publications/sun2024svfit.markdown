---
layout: publication
title: 'Svfit: Parameter-efficient Fine-tuning Of Large Pre-trained Models Using Singular
  Values'
authors: Sun et al.
conference: Nature Machine Intelligence
year: 2024
bibkey: sun2024svfit
citations: 417
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.05926'}]
tags: [Tools, Fine Tuning, Training Techniques, LLM for Code, RAG, Reinforcement Learning]
---
Large pre-trained models (LPMs) have demonstrated exceptional performance in
diverse natural language processing and computer vision tasks. However, fully
fine-tuning these models poses substantial memory challenges, particularly in
resource-constrained environments. Parameter-efficient fine-tuning (PEFT)
methods, such as LoRA, mitigate this issue by adjusting only a small subset of
parameters. Nevertheless, these methods typically employ random initialization
for low-rank matrices, which can lead to inefficiencies in gradient descent and
diminished generalizability due to suboptimal starting points. To address these
limitations, we propose SVFit, a novel PEFT approach that leverages singular
value decomposition (SVD) to initialize low-rank matrices using critical
singular values as trainable parameters. Specifically, SVFit performs SVD on
the pre-trained weight matrix to obtain the best rank-r approximation matrix,
emphasizing the most critical singular values that capture over 99% of the
matrix's information. These top-r singular values are then used as trainable
parameters to scale the fundamental subspaces of the matrix, facilitating rapid
domain adaptation. Extensive experiments across various pre-trained models in
natural language understanding, text-to-image generation, and image
classification tasks reveal that SVFit outperforms LoRA while requiring 16
times fewer trainable parameters.
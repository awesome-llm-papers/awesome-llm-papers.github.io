---
layout: publication
title: 'Qr-lora: Efficient And Disentangled Fine-tuning Via QR Decomposition For Customized
  Generation'
authors: Yang et al.
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2025
bibkey: yang2025qr
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.04599'}]
tags: [RAG, Training Techniques, Tools, Reinforcement Learning, Fine Tuning, Merging]
---
Existing text-to-image models often rely on parameter fine-tuning techniques such as Low-Rank Adaptation (LoRA) to customize visual attributes. However, when combining multiple LoRA models for content-style fusion tasks, unstructured modifications of weight matrices often lead to undesired feature entanglement between content and style attributes. We propose QR-LoRA, a novel fine-tuning framework leveraging QR decomposition for structured parameter updates that effectively separate visual attributes. Our key insight is that the orthogonal Q matrix naturally minimizes interference between different visual features, while the upper triangular R matrix efficiently encodes attribute-specific transformations. Our approach fixes both Q and R matrices while only training an additional task-specific \\(\Delta R\\) matrix. This structured design reduces trainable parameters to half of conventional LoRA methods and supports effective merging of multiple adaptations without cross-contamination due to the strong disentanglement properties between \\(\Delta R\\) matrices. Experiments demonstrate that QR-LoRA achieves superior disentanglement in content-style fusion tasks, establishing a new paradigm for parameter-efficient, disentangled fine-tuning in generative models.
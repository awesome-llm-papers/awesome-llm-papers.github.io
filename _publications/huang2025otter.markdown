---
layout: publication
title: 'OTTER: A Vision-language-action Model With Text-aware Visual Feature Extraction'
authors: Huang et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: huang2025otter
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.03734'}]
tags: [RAG, Training Techniques, Transformer, Model Architecture, Reinforcement Learning,
  Fine Tuning, Multimodal Models, Datasets]
---
Vision-Language-Action (VLA) models aim to predict robotic actions based on
visual observations and language instructions. Existing approaches require
fine-tuning pre-trained visionlanguage models (VLMs) as visual and language
features are independently fed into downstream policies, degrading the
pre-trained semantic alignments. We propose OTTER, a novel VLA architecture
that leverages these existing alignments through explicit, text-aware visual
feature extraction. Instead of processing all visual features, OTTER
selectively extracts and passes only task-relevant visual features that are
semantically aligned with the language instruction to the policy transformer.
This allows OTTER to keep the pre-trained vision-language encoders frozen.
Thereby, OTTER preserves and utilizes the rich semantic understanding learned
from large-scale pre-training, enabling strong zero-shot generalization
capabilities. In simulation and real-world experiments, OTTER significantly
outperforms existing VLA models, demonstrating strong zeroshot generalization
to novel objects and environments. Video, code, checkpoints, and dataset:
https://ottervla.github.io/.
---
layout: publication
title: 'Medvlm-r1: Incentivizing Medical Reasoning Capability Of Vision-language Models
  (vlms) Via Reinforcement Learning'
authors: Jiazhen Pan, Che Liu, Junde Wu, Fenglin Liu, Jiayuan Zhu, Hongwei Bran Li,
  Chen Chen, Cheng Ouyang, Daniel Rueckert
conference: No Venue
year: 2025
bibkey: pan2025medvlm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.19634'}]
tags: ["Ethics & Fairness", "Fine-Tuning", "Reinforcement Learning", "Tools", "Training Techniques"]
short_authors: Pan et al.
---
Reasoning is a critical frontier for advancing medical image analysis, where transparency and trustworthiness play a central role in both clinician trust and regulatory approval. Although Medical Visual Language Models (VLMs) show promise for radiological tasks, most existing VLMs merely produce final answers without revealing the underlying reasoning. To address this gap, we introduce MedVLM-R1, a medical VLM that explicitly generates natural language reasoning to enhance transparency and trustworthiness. Instead of relying on supervised fine-tuning (SFT), which often suffers from overfitting to training distributions and fails to foster genuine reasoning, MedVLM-R1 employs a reinforcement learning framework that incentivizes the model to discover human-interpretable reasoning paths without using any reasoning references. Despite limited training data (600 visual question answering samples) and model parameters (2B), MedVLM-R1 boosts accuracy from 55.11% to 78.22% across MRI, CT, and X-ray benchmarks, outperforming larger models trained on over a million samples. It also demonstrates robust domain generalization under out-of-distribution tasks. By unifying medical image analysis with explicit reasoning, MedVLM-R1 marks a pivotal step toward trustworthy and interpretable AI in clinical practice.

https://huggingface.co/discussions/paper/67c12bf4505a88e4a1866a35
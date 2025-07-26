---
layout: publication
title: 'Confidence Is All You Need: Few-shot RL Fine-tuning Of Language Models'
authors: Pengyi Li, Matvey Skripkin, Alexander Zubrey, Andrey Kuznetsov, Ivan Oseledets
conference: No Venue
year: 2025
bibkey: li2025confidence
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.06395'}]
tags: ["Few-Shot", "Fine-Tuning", "Reinforcement Learning", "Training Techniques"]
short_authors: Li et al.
---
Large language models (LLMs) excel at reasoning, yet post-training remains critical for aligning their behavior with task goals. Existing reinforcement learning (RL) methods often depend on costly human annotations or external reward models. We propose Reinforcement Learning via Self-Confidence (RLSC), which uses the model's own confidence as reward signals-eliminating the need for labels, preference models, or reward engineering. Applied to Qwen2.5-Math-7B with only 16 samples per question and 10 or 20 training steps, RLSC improves accuracy by +13.4% on AIME2024, +21.2% on MATH500, +21.7% on Minerva Math, +20.8% on Olympiadbench, and +9.7% on AMC23. RLSC provides a simple, scalable post-training method for inference models, requiring only a small number of samples and unlabelled supervision.

https://huggingface.co/discussions/paper/68492dd042e4f9106973f43c
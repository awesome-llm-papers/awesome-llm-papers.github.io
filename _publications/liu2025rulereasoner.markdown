---
layout: publication
title: 'Rulereasoner: Reinforced Rule-based Reasoning Via Domain-aware Dynamic Sampling'
authors: Yang Liu, Jiaqi Li, Zilong Zheng
conference: No Venue
year: 2025
bibkey: liu2025rulereasoner
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.08672'}]
tags: ["Applications", "Efficiency", "Reinforcement Learning", "Training Techniques"]
short_authors: Yang Liu, Jiaqi Li, Zilong Zheng
---
Rule-based reasoning has been acknowledged as one of the fundamental problems in reasoning, while deviations in rule formats, types, and complexity in real-world applications pose severe challenges. Recent studies have shown that large reasoning models (LRMs) have remarkable reasoning capabilities, and their performance is substantially enhanced by reinforcement learning (RL). However, it remains an open question whether small reasoning models (SRMs) can learn rule-based reasoning effectively with robust generalization across diverse tasks and domains. To address this, we introduce Reinforced Rule-based Reasoning, a.k.a. RuleReasoner, a simple yet effective method to conduct rule-based reasoning via a wide collection of curated tasks and a novel domain-aware dynamic sampling approach. Specifically, RuleReasoner resamples each training batch by updating the sampling weights of different domains based on historical rewards. This facilitates domain augmentation and flexible online learning schedules for RL, obviating the need for pre-hoc human-engineered mix-training recipes used in existing methods. Empirical evaluations on in-distribution (ID) and out-of-distribution (OOD) benchmarks reveal that RuleReasoner outperforms frontier LRMs by a significant margin (Delta4.1% average points on eight ID tasks and Delta10.4% average points on three OOD tasks over OpenAI-o1). Notably, our approach also exhibits higher computational efficiency compared to prior dynamic sampling methods for RL.

https://huggingface.co/discussions/paper/684936e842e4f9106973f461
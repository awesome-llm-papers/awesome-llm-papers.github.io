---
layout: publication
title: Enhancing The Reasoning Ability Of Multimodal Large Language Models Via Mixed
  Preference Optimization
authors: Weiyun Wang, Zhe Chen, Wenhai Wang, Yue Cao, Yangzhou Liu, Zhangwei Gao,
  Jinguo Zhu, Xizhou Zhu, Lewei Lu, Yu Qiao, Jifeng Dai
conference: No Venue
year: 2024
bibkey: wang2024enhancing
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/673acbc18127cd120caeb5c3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.10442'}]
tags: ["Datasets", "Efficiency", "Fine-Tuning", "Prompting", "Training Techniques"]
short_authors: Wang et al.
---
Existing open-source multimodal large language models (MLLMs) generally follow a training process involving pre-training and supervised fine-tuning. However, these models suffer from distribution shifts, which limit their multimodal reasoning, particularly in the Chain-of-Thought (CoT) performance. To address this, we introduce a preference optimization (PO) process to enhance the multimodal reasoning capabilities of MLLMs. Specifically, (1) on the data side, we design an automated preference data construction pipeline to create MMPR, a high-quality, large-scale multimodal reasoning preference dataset. and (2) on the model side, we explore integrating PO with MLLMs, developing a simple yet effective method, termed Mixed Preference Optimization (MPO), which boosts multimodal CoT performance. Our approach demonstrates improved performance across multiple benchmarks, particularly in multimodal reasoning tasks. Notably, our model, InternVL2-8B-MPO, achieves an accuracy of 67.0 on MathVista, outperforming InternVL2-8B by 8.7 points and achieving performance comparable to the 10x larger InternVL2-76B. We hope this study could inspire further advancements in MLLMs. Code, data, and model shall be publicly released.

https://huggingface.co/discussions/paper/673acbc18127cd120caeb5c3
---
layout: publication
title: 'LMM-R1: Empowering 3B Lmms With Strong Reasoning Abilities Through Two-stage
  Rule-based RL'
authors: Yingzhe Peng, Gongrui Zhang, Miaosen Zhang, Zhiyuan You, Jie Liu, Qipeng
  Zhu, Kai Yang, Xingzhong Xu, Xin Geng, Xu Yang
conference: No Venue
year: 2025
bibkey: peng2025lmm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.07536'}]
tags: ["Reinforcement Learning", "Tools", "Training Techniques"]
short_authors: Peng et al.
---
Enhancing reasoning in Large Multimodal Models (LMMs) faces unique challenges from the complex interplay between visual perception and logical reasoning, particularly in compact 3B-parameter architectures where architectural constraints limit reasoning capacity and modality alignment. While rule-based reinforcement learning (RL) excels in text-only domains, its multimodal extension confronts two critical barriers: (1) data limitations due to ambiguous answers and scarce complex reasoning examples, and (2) degraded foundational reasoning induced by multimodal pretraining. To address these challenges, we propose \method, a two-stage framework adapting rule-based RL for multimodal reasoning through Foundational Reasoning Enhancement (FRE) followed by Multimodal Generalization Training (MGT). The FRE stage first strengthens reasoning abilities using text-only data with rule-based RL, then the MGT stage generalizes these reasoning capabilities to multimodal domains. Experiments on Qwen2.5-VL-Instruct-3B demonstrate that \method achieves 4.83% and 4.5% average improvements over baselines in multimodal and text-only benchmarks, respectively, with a 3.63% gain in complex Football Game tasks. These results validate that text-based reasoning enhancement enables effective multimodal generalization, offering a data-efficient paradigm that bypasses costly high-quality multimodal training data.

https://huggingface.co/discussions/paper/67d04f268f79213c2fc0ba8b
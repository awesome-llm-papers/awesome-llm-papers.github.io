---
layout: publication
title: 'URSA: Understanding And Verifying Chain-of-thought Reasoning In Multimodal
  Mathematics'
authors: Ruilin Luo, Zhuofan Zheng, Yifan Wang, Yiyao Yu, Xinzhe Ni, Zicheng Lin,
  Jin Zeng, Yujiu Yang
conference: No Venue
year: 2025
bibkey: luo2025ursa
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/677f62cb407edfda4408dd5c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.04686'}]
tags: ["Datasets", "Efficiency", "Fine-Tuning", "Prompting", "Training Techniques"]
short_authors: Luo et al.
---
Chain-of-thought (CoT) reasoning has been widely applied in the mathematical reasoning of Large Language Models (LLMs). Recently, the introduction of derivative process supervision on CoT trajectories has sparked discussions on enhancing scaling capabilities during test time, thereby boosting the potential of these models. However, in multimodal mathematical reasoning, the scarcity of high-quality CoT training data has hindered existing models from achieving high-precision CoT reasoning and has limited the realization of reasoning potential during test time. In this work, we propose a three-module synthesis strategy that integrates CoT distillation, trajectory-format rewriting, and format unification. It results in a high-quality CoT reasoning instruction fine-tuning dataset in multimodal mathematics, MMathCoT-1M. We comprehensively validate the state-of-the-art (SOTA) performance of the trained URSA-7B model on multiple multimodal mathematical benchmarks. For test-time scaling, we introduce a data synthesis strategy that automatically generates process annotation datasets, known as DualMath-1.1M, focusing on both interpretation and logic. By further training URSA-7B on DualMath-1.1M, we transition from CoT reasoning capabilities to robust supervision abilities. The trained URSA-RM-7B acts as a verifier, effectively enhancing the performance of URSA-7B at test time. URSA-RM-7B also demonstrates excellent out-of-distribution (OOD) verifying capabilities, showcasing its generalization. Model weights, training data and code will be open-sourced.

https://huggingface.co/discussions/paper/677f62cb407edfda4408dd5c
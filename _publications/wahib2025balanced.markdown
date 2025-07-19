---
layout: publication
title: Balanced And Elastic End-to-end Training Of Dynamic Llms
authors: Wahib Mohamed, Soyturk Muhammed Abdullah, Unat Didem
conference: Proceedings of the 31st ACM Joint European Software Engineering Conference
  and Symposium on the Foundations of Software Engineering
year: 2025
bibkey: wahib2025balanced
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.14864'}]
tags: [Model Architecture, Pruning, Training Techniques, Efficiency And Optimization,
  Fine Tuning, LLM For Code, LLM for Code, Reinforcement Learning, Attention Mechanism,
  Large Scale Training]
---
To reduce computational and memory costs in Large Language Models (LLMs), dynamic workload reduction schemes like Mixture of Experts (MoEs), parameter pruning, layer freezing, sparse attention, early token exit, and Mixture of Depths (MoDs) have emerged. However, these methods introduce severe workload imbalances, limiting their practicality for large-scale distributed training. We propose DynMo, an autonomous dynamic load balancing solution that ensures optimal compute distribution when using pipeline parallelism in training dynamic models. DynMo adaptively balances workloads, dynamically packs tasks into fewer workers to free idle resources, and supports both multi-GPU single-node and multi-node systems. Compared to static training methods (Megatron-LM, DeepSpeed), DynMo accelerates training by up to 1.23x (MoEs), 3.18x (pruning), 2.23x (layer freezing), 4.02x (sparse attention), 4.52x (early exit), and 1.17x (MoDs). DynMo is available at https://anonymous.4open.science/r/DynMo-4D04/.
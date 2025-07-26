---
layout: publication
title: 'MM-RLHF: The Next Step Forward In Multimodal LLM Alignment'
authors: Yi-fan Zhang, Tao Yu, Haochen Tian, Chaoyou Fu, Peiyan Li, Jianshu Zeng,
  Wulin Xie, Yang Shi, Huanyu Zhang, Junkang Wu, Xue Wang, Yibo Hu, Bin Wen, Fan Yang,
  Zhang Zhang, Tingting Gao, di Zhang, Liang Wang, Rong Jin, Tieniu Tan
conference: No Venue
year: 2025
bibkey: zhang2025mm
additional_links: [{name: Code, url: 'https://mm-rlhf.github.io'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67b2ab598191c180b9c4ec10'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.10391'}]
tags: ["Has Code", "Reinforcement Learning"]
short_authors: Zhang et al.
---
Despite notable advancements in Multimodal Large Language Models (MLLMs), most state-of-the-art models have not undergone thorough alignment with human preferences. This gap exists because current alignment research has primarily achieved progress in specific areas (e.g., hallucination reduction), while the broader question of whether aligning models with human preferences can systematically enhance MLLM capability remains largely unexplored. To this end, we introduce MM-RLHF, a dataset containing 120k fine-grained, human-annotated preference comparison pairs. This dataset represents a substantial advancement over existing resources, offering superior size, diversity, annotation granularity, and quality. Leveraging this dataset, we propose several key innovations to improve both the quality of reward models and the efficiency of alignment algorithms. Notably, we introduce a Critique-Based Reward Model, which generates critiques of model outputs before assigning scores, offering enhanced interpretability and more informative feedback compared to traditional scalar reward mechanisms. Additionally, we propose Dynamic Reward Scaling, a method that adjusts the loss weight of each sample according to the reward signal, thereby optimizing the use of high-quality comparison pairs. Our approach is rigorously evaluated across 10 distinct dimensions and 27 benchmarks, with results demonstrating significant and consistent improvements in model performance. Specifically, fine-tuning LLaVA-ov-7B with MM-RLHF and our alignment algorithm leads to a 19.5% increase in conversational abilities and a 60% improvement in safety. We have open-sourced the preference dataset, reward model, training and evaluation code, as well as reward modeling and safety benchmarks. For more details, please visit our project page: https://mm-rlhf.github.io.

https://huggingface.co/discussions/paper/67b2ab598191c180b9c4ec10
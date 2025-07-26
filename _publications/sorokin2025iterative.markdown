---
layout: publication
title: Iterative Self-training For Code Generation Via Reinforced Re-ranking
authors: Nikita Sorokin, Ivan Sedykh, Valentin Malykh
conference: No Venue
year: 2025
bibkey: sorokin2025iterative
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67fe394e684ac7f04ce229e8'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.09643'}]
tags: ["Datasets", "Llm For Code", "Model Architecture", "Reinforcement Learning", "Training Techniques"]
short_authors: Nikita Sorokin, Ivan Sedykh, Valentin Malykh
---
Generating high-quality code that solves complex programming tasks is challenging, especially with current decoder-based models that produce highly stochastic outputs. In code generation, even minor errors can easily break the entire solution. Leveraging multiple sampled solutions can significantly improve the overall output quality. One effective way to enhance code generation is by pairing a code generation model with a reranker model, which selects the best solution from the generated samples. We propose a novel iterative self-training approach for self-training reranker models using Proximal Policy Optimization (PPO), aimed at improving both reranking accuracy and the overall code generation process. Unlike traditional PPO approaches, where the focus is on optimizing a generative model with a reward model, our approach emphasizes the development of a robust reward/reranking model. This model improves the quality of generated code through reranking and addresses problems and errors that the reward model might overlook during PPO alignment with the reranker. Our method iteratively refines the training dataset by re-evaluating outputs, identifying high-scoring negative examples, and incorporating them into the training loop, that boosting model performance. Our evaluation on the MultiPL-E dataset demonstrates that our 13.4B parameter model outperforms a 33B model in code generation quality while being three times faster. Moreover, it achieves performance comparable to GPT-4 and surpasses it in one programming language.

https://huggingface.co/discussions/paper/67fe394e684ac7f04ce229e8
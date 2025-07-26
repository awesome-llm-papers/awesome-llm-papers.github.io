---
layout: publication
title: Taming Llms By Scaling Learning Rates With Gradient Grouping
authors: Siyuan Li, Juanxi Tian, Zedong Wang, Xin Jin, Zicheng Liu, Wentao Zhang,
  Dan Xu
conference: No Venue
year: 2025
bibkey: li2025taming
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.01049'}]
tags: ["Efficiency", "Fine-Tuning", "Training Techniques"]
short_authors: Li et al.
---
Training large language models (LLMs) poses challenges due to their massive scale and heterogeneous architectures. While adaptive optimizers like AdamW help address gradient variations, they still struggle with efficient and effective parameter-wise learning rate estimation, resulting in training instability, slow convergence, and poor compatibility with parameter-efficient fine-tuning (PEFT) techniques. This work introduces Scaling with Gradient Grouping (SGG), an optimizer wrapper that improves adaptive learning rate estimation by dynamic grouping and group-specific scaling. SGG first groups gradient statistics in each layer into clusters and then applies cluster-specific scaling to calibrate learning rates for each parameter, thus imposing collective group-wise constraints while maintaining precise per-parameter adaptation. Experiments on diverse (M)LLM benchmarks show that SGG integrates seamlessly with existing optimizers, and offers consistent gains and faster convergence over baselines, with various model sizes. Its stability across varying batch sizes and learning rates establishes SGG as a robust choice for LLM optimization.

https://huggingface.co/discussions/paper/683e5b9b1167d9630159b2ef
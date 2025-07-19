---
layout: publication
title: Scaling Laws For Fine-grained Mixture Of Experts
authors: Krajewski et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: krajewski2024scaling
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.07871'}]
tags: [Scaling Laws, RAG, ICCV, Training Techniques, Transformer, Model Architecture,
  Efficiency And Optimization, Large Scale Training]
---
Mixture of Experts (MoE) models have emerged as a primary solution for
reducing the computational cost of Large Language Models. In this work, we
analyze their scaling properties, incorporating an expanded range of variables.
Specifically, we introduce a new hyperparameter, granularity, whose adjustment
enables precise control over the size of the experts. Building on this, we
establish scaling laws for fine-grained MoE, taking into account the number of
training tokens, model size, and granularity. Leveraging these laws, we derive
the optimal training configuration for a given computational budget. Our
findings not only show that MoE models consistently outperform dense
Transformers but also highlight that the efficiency gap between dense and MoE
models widens as we scale up the model size and training budget. Furthermore,
we demonstrate that the common practice of setting the size of experts in MoE
to mirror the feed-forward layer is not optimal at almost any computational
budget.
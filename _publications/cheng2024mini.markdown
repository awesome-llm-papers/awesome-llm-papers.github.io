---
layout: publication
title: 'MINI-LLM: Memory-efficient Structured Pruning For Large Language Models'
authors: Cheng Hongrong, Zhang Miao, Shi Javen Qinfeng
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2024
bibkey: cheng2024mini
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.11681'}]
tags: [EMNLP, Attention Mechanism, Tools, Model Architecture, Efficiency And Optimization,
  Pruning]
---
As Large Language Models (LLMs) grow dramatically in size, there is an
increasing trend in compressing and speeding up these models. Previous studies
have highlighted the usefulness of gradients for importance scoring in neural
network compressing, especially in pruning medium-size networks. However, the
substantial memory requirements involved in calculating gradients with
backpropagation impede the utilization of gradients in guiding LLM pruning. As
a result, most pruning strategies for LLMs rely on gradient-free criteria, such
as weight magnitudes or a mix of magnitudes and activations. In this paper, we
devise a hybrid pruning criterion, which appropriately integrates magnitude,
activation, and gradient to capitalize on feature map sensitivity for pruning
LLMs. To overcome memory requirement barriers, we estimate gradients using only
forward passes. Based on this, we propose a Memory-effIcieNt structured prunIng
procedure for LLMs (MINI-LLM) to remove no-critical channels and
multi-attention heads. Experimental results demonstrate the superior
performance of MINI-LLM over existing gradient-free methods on three LLMs:
LLaMA, BLOOM, and OPT across various downstream tasks (classification,
multiple-choice, and generation), while MINI-LLM maintains a GPU memory
footprint akin to gradient-free methods.
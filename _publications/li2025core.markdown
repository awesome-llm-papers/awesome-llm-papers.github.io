---
layout: publication
title: 'Core: Enhancing Metacognition With Label-free Self-evaluation In Lrms'
authors: Li et al.
conference: System
year: 2025
bibkey: li2025core
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.06087'}]
tags: [Tools, Training Techniques, Efficiency And Optimization, RSS, Evaluation, Fine
    Tuning, Dialogue & Multi-turn, IROS, NEURIPS, RAG, Datasets, Reinforcement Learning]
---
Large reasoning models (LRMs) have demonstrated impressive capabilities in domains like mathematics and program synthesis. Despite their strong performance, LRMs often exhibit overthinking -- excessive and redundant reasoning steps that introduce inefficiencies during inference. This phenomenon raises an important question for LRM self-evaluation: How can a model autonomously assess the correctness of its own reasoning trajectory without external labels? To address this, we propose Chain-of-Reasoning Embedding (CoRE), a series of hidden states in latent space to enable label-free self-evaluation on intermediate reasoning steps of LRMs, so as to enhance metacognition abilities for improved reasoning efficiency. By analyzing the geometric properties of the CoRE trajectories, we reveal that redundant reasoning usually presents cyclical fluctuations, which correspond to repetitive and unconscious reflection/exploration. Leveraging this insight, we further introduce a training-free, label-free self-evaluation framework, CoRE-Eval, to detect such patterns and dynamically determine whether to terminate reasoning early. Extensive experiments on mathematical reasoning benchmarks (GSM8K, MATH-500, and AIME) and across model sizes from 7B to 32B demonstrate that CoRE-Eval reduces chain-of-thought length by 13.7% to 33.2% while improving answer accuracy by around 10%, achieving 70.0% accuracy on the challenging AIME benchmark with the 32B model.
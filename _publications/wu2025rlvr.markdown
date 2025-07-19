---
layout: publication
title: 'Rlvr-world: Training World Models With Reinforcement Learning'
authors: Wu et al.
conference: Neural Networks
year: 2025
bibkey: wu2025rlvr
citations: 289
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.13934'}]
tags: [RAG, Training Techniques, ICANN, GPT, Agentic, Tools, Evaluation, Reinforcement
    Learning]
---
World models predict state transitions in response to actions and are increasingly developed across diverse modalities. However, standard training objectives such as maximum likelihood estimation (MLE) often misalign with task-specific goals of world models, i.e., transition prediction metrics like accuracy or perceptual quality. In this paper, we present RLVR-World, a unified framework that leverages reinforcement learning with verifiable rewards (RLVR) to directly optimize world models for such metrics. Despite formulating world modeling as autoregressive prediction of tokenized sequences, RLVR-World evaluates metrics of decoded predictions as verifiable rewards. We demonstrate substantial performance gains on both language- and video-based world models across domains, including text games, web navigation, and robot manipulation. Our work indicates that, beyond recent advances in reasoning language models, RLVR offers a promising post-training paradigm for enhancing the utility of generative models more broadly.
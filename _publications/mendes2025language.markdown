---
layout: publication
title: Language Models Can Self-improve At State-value Estimation For Better Search
authors: Mendes Ethan, Ritter Alan
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: mendes2025language
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.02878'}]
tags: [RAG, EMNLP, Training Techniques, GPT, Model Architecture, Reinforcement Learning]
---
Collecting ground-truth rewards or human demonstrations for multi-step reasoning tasks is often prohibitively expensive and time consuming, especially in interactive domains like web tasks. To address this bottleneck, we present self-taught lookahead (STL), a self-supervised method that leverages state-transition dynamics to improve a value model capable of effectively guiding language model-controlled search without any labeled data. We find that moderately sized (8 billion parameters) open-weight value models improved with STL can match the performance of using a gpt-4o value model. Furthermore, we find that specialized value models learned with STL can be deployed with computationally lightweight search algorithms, achieving performance that matches that of more expensive tree search methods, while reducing costs by an order of magnitude.
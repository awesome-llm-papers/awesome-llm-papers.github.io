---
layout: publication
title: 'Entropy-uid: A Method For Optimizing Information Density'
authors: Shou Xinpeng
conference: Physical Review B
year: 2025
bibkey: shou2025entropy
citations: 275
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.14366'}]
tags: [RAG, GPT, Alt, Evaluation, Model Architecture, Efficiency And Optimization,
  Language Modeling, Datasets]
---
Balanced and efficient information flow is essential for optimizing language
generation models. In this work, we propose Entropy-UID, a new token selection
method that balances entropy and Uniform Information Density (UID) principles
for enhanced efficiency of text generation. Our approach adaptively adjusts
token selection by jointly minimizing entropy and surprisal, promoting more
even information distribution across generated sequences. Theoretical
validation demonstrates that Entropy-UID optimally reduces information spikes
while maintaining fluency and coherence. The method has been evulated using
information-theoretic metrics on multiple benchmark datasets, including
WikiText-2, OpenWebText, and WMT. Experimental results show that Entropy-UID
achieves lower surprisal and entropy variance compared to standard GPT-2 and
alternative heuristics, leading to more balanced and human-like text
generation. Our findings point towards the potential of leveraging
information-theoretic constraints to refine token selection strategies in
autoregressive language models.
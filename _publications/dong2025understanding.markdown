---
layout: publication
title: Understanding And Mitigating Cross-lingual Privacy Leakage Via Language-specific
  And Universal Privacy Neurons
authors: Dong et al.
conference: IEEE Transactions on Information Forensics and Security
year: 2025
bibkey: dong2025understanding
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.00759'}]
tags: [Alt, Reinforcement Learning, Training Techniques, Security]
---
Large Language Models (LLMs) trained on massive data capture rich information embedded in the training data. However, this also introduces the risk of privacy leakage, particularly involving personally identifiable information (PII). Although previous studies have shown that this risk can be mitigated through methods such as privacy neurons, they all assume that both the (sensitive) training data and user queries are in English. We show that they cannot defend against the privacy leakage in cross-lingual contexts: even if the training data is exclusively in one language, these (private) models may still reveal private information when queried in another language. In this work, we first investigate the information flow of cross-lingual privacy leakage to give a better understanding. We find that LLMs process private information in the middle layers, where representations are largely shared across languages. The risk of leakage peaks when converted to a language-specific space in later layers. Based on this, we identify privacy-universal neurons and language-specific privacy neurons. Privacy-universal neurons influence privacy leakage across all languages, while language-specific privacy neurons are only related to specific languages. By deactivating these neurons, the cross-lingual privacy leakage risk is reduced by 23.3%-31.6%.
---
layout: publication
title: Towards Building Efficient Sentence BERT Models Using Layer Pruning
authors: Shelke Anushka, Savant Riya, Joshi Raviraj
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2024
bibkey: shelke2024towards
citations: 4978
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.14168'}]
tags: [Training Techniques, EMNLP, BERT, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning, Fine Tuning, Pruning]
---
This study examines the effectiveness of layer pruning in creating efficient
Sentence BERT (SBERT) models. Our goal is to create smaller sentence embedding
models that reduce complexity while maintaining strong embedding similarity. We
assess BERT models like Muril and MahaBERT-v2 before and after pruning,
comparing them with smaller, scratch-trained models like MahaBERT-Small and
MahaBERT-Smaller. Through a two-phase SBERT fine-tuning process involving
Natural Language Inference (NLI) and Semantic Textual Similarity (STS), we
evaluate the impact of layer reduction on embedding quality. Our findings show
that pruned models, despite fewer layers, perform competitively with fully
layered versions. Moreover, pruned models consistently outperform similarly
sized, scratch-trained models, establishing layer pruning as an effective
strategy for creating smaller, efficient embedding models. These results
highlight layer pruning as a practical approach for reducing computational
demand while preserving high-quality embeddings, making SBERT models more
accessible for languages with limited technological resources.
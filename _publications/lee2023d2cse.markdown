---
layout: publication
title: 'D2CSE: Difference-aware Deep Continuous Prompts For Contrastive Sentence Embeddings'
authors: Lee Hyunjae
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2023
bibkey: lee2023d2cse
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.08991'}]
tags: [Model Architecture, Prompting, Training Techniques, Fine Tuning, Evaluation,
  ACL, NAACL, Datasets, Reinforcement Learning]
---
This paper describes Difference-aware Deep continuous prompt for Contrastive
Sentence Embeddings (D2CSE) that learns sentence embeddings. Compared to
state-of-the-art approaches, D2CSE computes sentence vectors that are
exceptional to distinguish a subtle difference in similar sentences by
employing a simple neural architecture for continuous prompts. Unlike existing
architectures that require multiple pretrained language models (PLMs) to
process a pair of the original and corrupted (subtly modified) sentences, D2CSE
avoids cumbersome fine-tuning of multiple PLMs by only optimizing continuous
prompts by performing multiple tasks -- i.e., contrastive learning and
conditional replaced token detection all done in a self-guided manner. D2CSE
overloads a single PLM on continuous prompts and greatly saves memory
consumption as a result. The number of training parameters in D2CSE is reduced
to about 1% of existing approaches while substantially improving the quality
of sentence embeddings. We evaluate D2CSE on seven Semantic Textual Similarity
(STS) benchmarks, using three different metrics, namely, Spearman's rank
correlation, recall@K for a retrieval task, and the anisotropy of an embedding
space measured in alignment and uniformity. Our empirical results suggest that
shallow (not too meticulously devised) continuous prompts can be honed
effectively for multiple NLP tasks and lead to improvements upon existing
state-of-the-art approaches.
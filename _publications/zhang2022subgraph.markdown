---
layout: publication
title: Subgraph Retrieval Enhanced Model For Multi-hop Knowledge Base Question Answering
authors: Zhang et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: zhang2022subgraph
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.13296'}]
tags: [Ethics And Bias, Tools, Fine Tuning, Training Techniques, ACL, Reinforcement
    Learning]
---
Recent works on knowledge base question answering (KBQA) retrieve subgraphs
for easier reasoning. A desired subgraph is crucial as a small one may exclude
the answer but a large one might introduce more noises. However, the existing
retrieval is either heuristic or interwoven with the reasoning, causing
reasoning on the partial subgraphs, which increases the reasoning bias when the
intermediate supervision is missing. This paper proposes a trainable subgraph
retriever (SR) decoupled from the subsequent reasoning process, which enables a
plug-and-play framework to enhance any subgraph-oriented KBQA model. Extensive
experiments demonstrate SR achieves significantly better retrieval and QA
performance than existing retrieval methods. Via weakly supervised pre-training
as well as the end-to-end fine-tuning, SRl achieves new state-of-the-art
performance when combined with NSM, a subgraph-oriented reasoner, for
embedding-based KBQA methods.
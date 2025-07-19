---
layout: publication
title: Knowledge Graph-augmented Language Models For Knowledge-grounded Dialogue Generation
authors: Kang et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2023
bibkey: kang2023knowledge
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.18846'}]
tags: [RAG, Tools, EMNLP, Datasets]
---
Language models have achieved impressive performances on dialogue generation
tasks. However, when generating responses for a conversation that requires
factual knowledge, they are far from perfect, due to an absence of mechanisms
to retrieve, encode, and reflect the knowledge in the generated responses. Some
knowledge-grounded dialogue generation methods tackle this problem by
leveraging facts from Knowledge Graphs (KGs); however, they do not guarantee
that the model utilizes a relevant piece of knowledge from the KG. To overcome
this limitation, we propose SUbgraph Retrieval-augmented GEneration (SURGE), a
framework for generating context-relevant and knowledge-grounded dialogues with
the KG. Specifically, our SURGE framework first retrieves the relevant subgraph
from the KG, and then enforces consistency across facts by perturbing their
word embeddings conditioned by the retrieved subgraph. Then, we utilize
contrastive learning to ensure that the generated texts have high similarity to
the retrieved subgraphs. We validate our SURGE framework on OpendialKG and
KOMODIS datasets, showing that it generates high-quality dialogues that
faithfully reflect the knowledge from KG.
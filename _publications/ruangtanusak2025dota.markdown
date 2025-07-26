---
layout: publication
title: 'Dota-rag: Dynamic Of Thought Aggregation RAG'
authors: Saksorn Ruangtanusak, Natthapath Rungseesiripak, Peerawat Rojratchadakorn,
  Monthol Charattrakool, Natapong Nitarach
conference: No Venue
year: 2025
bibkey: ruangtanusak2025dota
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.12571'}]
tags: ["RAG"]
short_authors: Ruangtanusak et al.
---
In this paper, we introduce DoTA-RAG (Dynamic-of-Thought Aggregation RAG), a retrieval-augmented generation system optimized for high-throughput, large-scale web knowledge indexes. Traditional RAG pipelines often suffer from high latency and limited accuracy over massive, diverse datasets. DoTA-RAG addresses these challenges with a three-stage pipeline: query rewriting, dynamic routing to specialized sub-indexes, and multi-stage retrieval and ranking. We further enhance retrieval by evaluating and selecting a superior embedding model, re-embedding the large FineWeb-10BT corpus. Moreover, we create a diverse Q&A dataset of 500 questions generated via the DataMorgana setup across a broad range of WebOrganizer topics and formats. DoTA-RAG improves the answer correctness score from 0.752 (baseline, using LiveRAG pre-built vector store) to 1.478 while maintaining low latency, and it achieves a 0.929 correctness score on the Live Challenge Day. These results highlight DoTA-RAG's potential for practical deployment in domains requiring fast, reliable access to large and evolving knowledge sources.

https://huggingface.co/discussions/paper/6850cba15e07650ecce88fd3
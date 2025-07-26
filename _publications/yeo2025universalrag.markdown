---
layout: publication
title: 'Universalrag: Retrieval-augmented Generation Over Multiple Corpora With Diverse
  Modalities And Granularities'
authors: Woongyeong Yeo, Kangsan Kim, Soyeong Jeong, Jinheon Baek, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: yeo2025universalrag
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.20734'}]
tags: ["RAG"]
short_authors: Yeo et al.
---
Retrieval-Augmented Generation (RAG) has shown substantial promise in improving factual accuracy by grounding model responses with external knowledge relevant to queries. However, most existing RAG approaches are limited to a text-only corpus, and while recent efforts have extended RAG to other modalities such as images and videos, they typically operate over a single modality-specific corpus. In contrast, real-world queries vary widely in the type of knowledge they require, which a single type of knowledge source cannot address. To address this, we introduce UniversalRAG, a novel RAG framework designed to retrieve and integrate knowledge from heterogeneous sources with diverse modalities and granularities. Specifically, motivated by the observation that forcing all modalities into a unified representation space derived from a single combined corpus causes a modality gap, where the retrieval tends to favor items from the same modality as the query, we propose a modality-aware routing mechanism that dynamically identifies the most appropriate modality-specific corpus and performs targeted retrieval within it. Also, beyond modality, we organize each modality into multiple granularity levels, enabling fine-tuned retrieval tailored to the complexity and scope of the query. We validate UniversalRAG on 8 benchmarks spanning multiple modalities, showing its superiority over modality-specific and unified baselines.

https://huggingface.co/discussions/paper/6811966ae20ba7d0683b8b0e
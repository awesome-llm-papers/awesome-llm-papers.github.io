---
layout: publication
title: 'Wikivideo: Article Generation From Multiple Videos'
authors: Alexander Martin, Reno Kriz, William Gantt Walden, Kate Sanders, Hannah Recknor,
  Eugene Yang, Francis Ferraro, Benjamin van Durme
conference: No Venue
year: 2025
bibkey: martin2025wikivideo
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.00939'}]
tags: ["RAG"]
short_authors: Martin et al.
---
We present the challenging task of automatically creating a high-level Wikipedia-style article that aggregates information from multiple diverse videos about real-world events, such as natural disasters or political elections. Videos are intuitive sources for retrieval-augmented generation (RAG), but most contemporary RAG workflows focus heavily on text and existing methods for video-based summarization focus on low-level scene understanding rather than high-level event semantics. To close this gap, we introduce WikiVideo, a benchmark consisting of expert-written articles and densely annotated videos that provide evidence for articles' claims, facilitating the integration of video into RAG pipelines and enabling the creation of in-depth content that is grounded in multimodal sources. We further propose Collaborative Article Generation (CAG), a novel interactive method for article creation from multiple videos. CAG leverages an iterative interaction between an r1-style reasoning model and a VideoLLM to draw higher level inferences about the target event than is possible with VideoLLMs alone, which fixate on low-level visual features. We benchmark state-of-the-art VideoLLMs and CAG in both oracle retrieval and RAG settings and find that CAG consistently outperforms alternative methods, while suggesting intriguing avenues for future work.

https://huggingface.co/discussions/paper/67efffad5e8b84102499ec6e
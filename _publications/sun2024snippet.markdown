---
layout: publication
title: Snippet-based Conversational Recommender System
authors: Sun et al.
conference: The 41st International ACM SIGIR Conference on Research &amp; Development
  in Information Retrieval
year: 2024
bibkey: sun2024snippet
citations: 211
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.06064'}]
tags: [RAG, Training Techniques, SIGIR, Fine Tuning, Datasets]
---
Conversational Recommender Systems (CRS) engage users in interactive
dialogues to gather preferences and provide personalized recommendations. While
existing studies have advanced conversational strategies, they often rely on
predefined attributes or expensive, domain-specific annotated datasets, which
limits their flexibility in handling diverse user preferences and adaptability
across domains. We propose SnipRec, a novel resource-efficient approach that
leverages user-generated content, such as customer reviews, to capture a
broader range of user expressions. By employing large language models to map
reviews and user responses into concise snippets, SnipRec represents user
preferences and retrieves relevant items without the need for intensive manual
data collection or fine-tuning. Experiments across the restaurant, book, and
clothing domains show that snippet-based representations outperform document-
and sentence-based representations, achieving Hits@10 of 0.25-0.55 with 3,000
to 10,000 candidate items while successfully handling free-form user responses.
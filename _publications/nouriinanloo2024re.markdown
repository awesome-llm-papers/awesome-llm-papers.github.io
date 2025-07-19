---
layout: publication
title: 'Re-ranking Step By Step: Investigating Pre-filtering For Re-ranking With Large
  Language Models'
authors: Nouriinanloo Baharan, Lamothe Maxime
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: nouriinanloo2024re
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.18740'}]
tags: [RAG, EMNLP, GPT, Model Architecture]
---
Large Language Models (LLMs) have been revolutionizing a myriad of natural
language processing tasks with their diverse zero-shot capabilities. Indeed,
existing work has shown that LLMs can be used to great effect for many tasks,
such as information retrieval (IR), and passage ranking. However, current
state-of-the-art results heavily lean on the capabilities of the LLM being
used. Currently, proprietary, and very large LLMs such as GPT-4 are the highest
performing passage re-rankers. Hence, users without the resources to leverage
top of the line LLMs, or ones that are closed source, are at a disadvantage. In
this paper, we investigate the use of a pre-filtering step before passage
re-ranking in IR. Our experiments show that by using a small number of human
generated relevance scores, coupled with LLM relevance scoring, it is
effectively possible to filter out irrelevant passages before re-ranking. Our
experiments also show that this pre-filtering then allows the LLM to perform
significantly better at the re-ranking task. Indeed, our results show that
smaller models such as Mixtral can become competitive with much larger
proprietary models (e.g., ChatGPT and GPT-4).
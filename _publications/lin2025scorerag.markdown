---
layout: publication
title: 'Scorerag: A Retrieval-augmented Generation Framework With Consistency-relevance
  Scoring And Structured Summarization For News Generation'
authors: Lin Pei-yun, Tsai Yen-lung
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2021'
year: 2025
bibkey: lin2025scorerag
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.03704'}]
tags: [Tools, Evaluation, ACL, EMNLP, RAG]
---
This research introduces ScoreRAG, an approach to enhance the quality of automated news generation. Despite advancements in Natural Language Processing and large language models, current news generation methods often struggle with hallucinations, factual inconsistencies, and lack of domain-specific expertise when producing news articles. ScoreRAG addresses these challenges through a multi-stage framework combining retrieval-augmented generation, consistency relevance evaluation, and structured summarization. The system first retrieves relevant news documents from a vector database, maps them to complete news items, and assigns consistency relevance scores based on large language model evaluations. These documents are then reranked according to relevance, with low-quality items filtered out. The framework proceeds to generate graded summaries based on relevance scores, which guide the large language model in producing complete news articles following professional journalistic standards. Through this methodical approach, ScoreRAG aims to significantly improve the accuracy, coherence, informativeness, and professionalism of generated news articles while maintaining stability and consistency throughout the generation process. The code and demo are available at: https://github.com/peiyun2260/ScoreRAG.
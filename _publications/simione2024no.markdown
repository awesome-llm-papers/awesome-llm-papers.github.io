---
layout: publication
title: 'No Dataset Needed For Downstream Knowledge Benchmarking: Response Dispersion
  Inversely Correlates With Accuracy On Domain-specific QA'
authors: Simione Robert L Ii
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: simione2024no
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.13624'}]
tags: [RAG, Prompting, Tools, Evaluation, Reinforcement Learning, AAAI, Datasets]
---
This research seeks to obviate the need for creating QA datasets and grading
(chatbot) LLM responses when comparing LLMs' knowledge in specific topic
domains. This is done in an entirely end-user centric way without need for
access to any inner workings of the LLM, so long as it can be prompted and
given a random seed to create different generations to the same prompt. The
paper does this by, for a given topic domain, defining the "response
dispersion" of an LLM by repeatedly asking an LLM the same opinion question
about that topic domain. Namely, the response dispersion is the count of
singular values needed to explain 95% of the variance in the embedding matrix
of the LLM's responses. It is found that the response dispersion is inversely
correlated with accuracy on relevant QA evaluations (average spearman rank
correlation stronger than -.59). A use-case analysis shows that when comparing
two different LLMs on the same topic domain, comparing their response
dispersion is a suitable replacement for comparing their QA accuracy between
74% and 89% of the time, the range depending on certain reasonable
accuracy-difference tolerances that may be acceptable to an end-user in
exchange for the labor being saved using response dispersion instead of QA
accuracy for comparison. Two response embeddings are studied for creating the
embedding matrix in this study, one is from OpenAI's APIs and one is a novel
embedding, here named reference sentence similarity embeddings, that can be
computed locally and performs very nearly as well in calculating response
dispersion. Also in this research, a pre-existing dataset called the IRC-Wiki
Trivia dataset, originally developed for trivia games, has been re-purposed,
curated, and the curation, called IRC-WikiTriviaQA, is made available for the
purpose of this research.
---
layout: publication
title: Improving Accuracy Of GPT-3/4 Results On Biomedical Data Using A Retrieval-augmented
  Language Model
authors: David Soong et al.
conference: PLOS Digital Health
year: 2023
citations: 17
bibkey: soong2023improving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.17116'}]
tags: [Model Architecture, GPT, RAG, Training Techniques, Evaluation]
---
Large language models (LLMs) have made significant advancements in natural
language processing (NLP). Broad corpora capture diverse patterns but can
introduce irrelevance, while focused corpora enhance reliability by reducing
misleading information. Training LLMs on focused corpora poses computational
challenges. An alternative approach is to use a retrieval-augmentation (RetA)
method tested in a specific domain.
  To evaluate LLM performance, OpenAI's GPT-3, GPT-4, Bing's Prometheus, and a
custom RetA model were compared using 19 questions on diffuse large B-cell
lymphoma (DLBCL) disease. Eight independent reviewers assessed responses based
on accuracy, relevance, and readability (rated 1-3).
  The RetA model performed best in accuracy (12/19 3-point scores, total=47)
and relevance (13/19, 50), followed by GPT-4 (8/19, 43; 11/19, 49). GPT-4
received the highest readability scores (17/19, 55), followed by GPT-3 (15/19,
53) and the RetA model (11/19, 47). Prometheus underperformed in accuracy (34),
relevance (32), and readability (38).
  Both GPT-3.5 and GPT-4 had more hallucinations in all 19 responses compared
to the RetA model and Prometheus. Hallucinations were mostly associated with
non-existent references or fabricated efficacy data.
  These findings suggest that RetA models, supplemented with domain-specific
corpora, may outperform general-purpose LLMs in accuracy and relevance within
specific domains. However, this evaluation was limited to specific questions
and metrics and may not capture challenges in semantic search and other NLP
tasks. Further research will explore different LLM architectures, RetA
methodologies, and evaluation methods to assess strengths and limitations more
comprehensively.
---
layout: publication
title: 'Understanding Biases In Chatgpt-based Recommender Systems: Provider Fairness,
  Temporal Stability, And Recency'
authors: Yashar Deldjoo
conference: Arxiv
year: 2024
citations: 18
bibkey: deldjoo2024understanding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.10545'}, {name: Code,
    url: 'https://github.com/yasdel/Benchmark_RecLLM_Fairness'}]
tags: [Ethics and Bias, GPT, RAG, Few-Shot, RecSys, Tools, Reinforcement Learning,
  In-Context Learning, Has Code, Fairness, Bias Mitigation, Prompting, Model Architecture]
---
This paper explores the biases in ChatGPT-based recommender systems, focusing
on provider fairness (item-side fairness). Through extensive experiments and
over a thousand API calls, we investigate the impact of prompt design
strategies-including structure, system role, and intent-on evaluation metrics
such as provider fairness, catalog coverage, temporal stability, and recency.
The first experiment examines these strategies in classical top-K
recommendations, while the second evaluates sequential in-context learning
(ICL).
  In the first experiment, we assess seven distinct prompt scenarios on top-K
recommendation accuracy and fairness. Accuracy-oriented prompts, like Simple
and Chain-of-Thought (COT), outperform diversification prompts, which, despite
enhancing temporal freshness, reduce accuracy by up to 50%. Embedding fairness
into system roles, such as "act as a fair recommender," proved more effective
than fairness directives within prompts. Diversification prompts led to
recommending newer movies, offering broader genre distribution compared to
traditional collaborative filtering (CF) models.
  The second experiment explores sequential ICL, comparing zero-shot and
few-shot ICL. Results indicate that including user demographic information in
prompts affects model biases and stereotypes. However, ICL did not consistently
improve item fairness and catalog coverage over zero-shot learning. Zero-shot
learning achieved higher NDCG and coverage, while ICL-2 showed slight
improvements in hit rate (HR) when age-group context was included. Our study
provides insights into biases of RecLLMs, particularly in provider fairness and
catalog coverage. By examining prompt design, learning strategies, and system
roles, we highlight the potential and challenges of integrating LLMs into
recommendation systems. Further details can be found at
https://github.com/yasdel/Benchmark_RecLLM_Fairness.
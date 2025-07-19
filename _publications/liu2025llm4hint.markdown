---
layout: publication
title: 'Llm4hint: Leveraging Large Language Models For Hint Recommendation In Offline
  Query Optimization'
authors: Liu et al.
conference: Proceedings of the 17th ACM Conference on Recommender Systems
year: 2025
bibkey: liu2025llm4hint
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.03384'}]
tags: [Prompting, Fine Tuning, Training Techniques, Efficiency And Optimization, RAG,
  RecSys]
---
Query optimization is essential for efficient SQL query execution in DBMS, and remains attractive over time due to the growth of data volumes and advances in hardware. Existing traditional optimizers struggle with the cumbersome hand-tuning required for complex workloads, and the learning-based methods face limitations in ensuring generalization. With the great success of Large Language Model (LLM) across diverse downstream tasks, this paper explores how LLMs can be incorporated to enhance the generalization of learned optimizers. Though promising, such an incorporation still presents challenges, mainly including high model inference latency, and the substantial fine-tuning cost and suboptimal performance due to inherent discrepancy between the token sequences in LLM and structured SQL execution plans with rich numerical features.
  In this paper, we focus on recurring queries in offline optimization to alleviate the issue of high inference latency, and propose \textbf\{LLM4Hint\} that leverages moderate-sized backbone LLMs to recommend query optimization hints. LLM4Hint achieves the goals through: (i) integrating a lightweight model to produce a soft prompt, which captures the data distribution in DBMS and the SQL predicates to provide sufficient optimization features while simultaneously reducing the context length fed to the LLM, (ii) devising a query rewriting strategy using a larger commercial LLM, so as to simplify SQL semantics for the backbone LLM and reduce fine-tuning costs, and (iii) introducing an explicit matching prompt to facilitate alignment between the LLM and the lightweight model, which can accelerate convergence of the combined model. Experiments show that LLM4Hint, by leveraging the LLM's stronger capability to understand the query statement, can outperform the state-of-the-art learned optimizers in terms of both effectiveness and generalization.
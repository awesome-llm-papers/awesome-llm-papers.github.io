---
layout: publication
title: 'Gsm-symbolic: Understanding The Limitations Of Mathematical Reasoning In Large
  Language Models'
authors: Mirzadeh et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 5: Industry Track)'
year: 2024
bibkey: mirzadeh2024gsm
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.05229'}]
tags: [Training Techniques, Evaluation, ACL, RAG, Datasets, Reinforcement Learning,
  Alt]
---
Recent advancements in Large Language Models (LLMs) have sparked interest in
their formal reasoning capabilities, particularly in mathematics. The GSM8K
benchmark is widely used to assess the mathematical reasoning of models on
grade-school-level questions. While the performance of LLMs on GSM8K has
significantly improved in recent years, it remains unclear whether their
mathematical reasoning capabilities have genuinely advanced, raising questions
about the reliability of the reported metrics. To address these concerns, we
conduct a large-scale study on several SOTA open and closed models. To overcome
the limitations of existing evaluations, we introduce GSM-Symbolic, an improved
benchmark created from symbolic templates that allow for the generation of a
diverse set of questions. GSM-Symbolic enables more controllable evaluations,
providing key insights and more reliable metrics for measuring the reasoning
capabilities of models.Our findings reveal that LLMs exhibit noticeable
variance when responding to different instantiations of the same question.
Specifically, the performance of all models declines when only the numerical
values in the question are altered in the GSM-Symbolic benchmark. Furthermore,
we investigate the fragility of mathematical reasoning in these models and show
that their performance significantly deteriorates as the number of clauses in a
question increases. We hypothesize that this decline is because current LLMs
cannot perform genuine logical reasoning; they replicate reasoning steps from
their training data. Adding a single clause that seems relevant to the question
causes significant performance drops (up to 65%) across all state-of-the-art
models, even though the clause doesn't contribute to the reasoning chain needed
for the final answer. Overall, our work offers a more nuanced understanding of
LLMs' capabilities and limitations in mathematical reasoning.
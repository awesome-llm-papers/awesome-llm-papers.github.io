---
layout: publication
title: 'Rag-zeval: Towards Robust And Interpretable Evaluation On RAG Responses Through
  End-to-end Rule-guided Reasoning'
authors: Li et al.
conference: Nature
year: 2025
bibkey: li2025rag
citations: 261
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.22430'}]
tags: [Interpretability And Explainability, RAG, Prompting, Agentic, Tools, Evaluation,
  Reinforcement Learning]
---
Robust evaluation is critical for deploying trustworthy retrieval-augmented generation (RAG) systems. However, current LLM-based evaluation frameworks predominantly rely on directly prompting resource-intensive models with complex multi-stage prompts, underutilizing models' reasoning capabilities and introducing significant computational cost. In this paper, we present RAG-Zeval (RAG-Zero Evaluator), a novel end-to-end framework that formulates faithfulness and correctness evaluation as a rule-guided reasoning task. Our approach trains evaluators with reinforcement learning, facilitating compact models to generate comprehensive and sound assessments with detailed explanation in one-pass. We introduce a ranking-based outcome reward mechanism, using preference judgments rather than absolute scores, to address the challenge of obtaining precise pointwise reward signals. To this end, we synthesize the ranking references by generating quality-controlled responses with zero human annotation. Experiments demonstrate RAG-Zeval's superior performance, achieving the strongest correlation with human judgments and outperforming baselines that rely on LLMs with 10-100 times more parameters. Our approach also exhibits superior interpretability in response evaluation.
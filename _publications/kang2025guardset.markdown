---
layout: publication
title: 'Guardset-x: Massive Multi-domain Safety Policy-grounded Guardrail Dataset'
authors: Kang et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2025
bibkey: kang2025guardset
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.19054'}]
tags: [Datasets, RAG, EMNLP, Prompting, Evaluation, Reinforcement Learning, Security,
  Applications, Responsible AI]
---
As LLMs become widespread across diverse applications, concerns about the security and safety of LLM interactions have intensified. Numerous guardrail models and benchmarks have been developed to ensure LLM content safety. However, existing guardrail benchmarks are often built upon ad hoc risk taxonomies that lack a principled grounding in standardized safety policies, limiting their alignment with real-world operational requirements. Moreover, they tend to overlook domain-specific risks, while the same risk category can carry different implications across different domains. To bridge these gaps, we introduce GuardSet-X, the first massive multi-domain safety policy-grounded guardrail dataset. GuardSet-X offers: (1) broad domain coverage across eight safety-critical domains, such as finance, law, and codeGen; (2) policy-grounded risk construction based on authentic, domain-specific safety guidelines; (3) diverse interaction formats, encompassing declarative statements, questions, instructions, and multi-turn conversations; (4) advanced benign data curation via detoxification prompting to challenge over-refusal behaviors; and (5) \textbf\{attack-enhanced instances\} that simulate adversarial inputs designed to bypass guardrails. Based on GuardSet-X, we benchmark 19 advanced guardrail models and uncover a series of findings, such as: (1) All models achieve varied F1 scores, with many demonstrating high variance across risk categories, highlighting their limited domain coverage and insufficient handling of domain-specific safety concerns; (2) As models evolve, their coverage of safety risks broadens, but performance on common risk categories may decrease; (3) All models remain vulnerable to optimized adversarial attacks. We believe that \dataset and the unique insights derived from our evaluations will advance the development of policy-aligned and resilient guardrail systems.
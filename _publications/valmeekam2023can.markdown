---
layout: publication
title: Can Large Language Models Really Improve By Self-critiquing Their Own Plans?
authors: Valmeekam Karthik, Marquez Matthew, Kambhampati Subbarao
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: valmeekam2023can
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.08118'}]
tags: [Model Architecture, Tools, EMNLP, GPT]
---
There have been widespread claims about Large Language Models (LLMs) being
able to successfully verify or self-critique their candidate solutions in
reasoning problems in an iterative mode. Intrigued by those claims, in this
paper we set out to investigate the verification/self-critiquing abilities of
large language models in the context of planning. We evaluate a planning system
that employs LLMs for both plan generation and verification. We assess the
verifier LLM's performance against ground-truth verification, the impact of
self-critiquing on plan generation, and the influence of varying feedback
levels on system performance. Using GPT-4, a state-of-the-art LLM, for both
generation and verification, our findings reveal that self-critiquing appears
to diminish plan generation performance, especially when compared to systems
with external, sound verifiers and the LLM verifiers in that system produce a
notable number of false positives, compromising the system's reliability.
Additionally, the nature of feedback, whether binary or detailed, showed
minimal impact on plan generation. Collectively, our results cast doubt on the
effectiveness of LLMs in a self-critiquing, iterative framework for planning
tasks.
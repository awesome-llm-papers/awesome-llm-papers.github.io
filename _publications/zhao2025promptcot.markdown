---
layout: publication
title: 'Promptcot: Synthesizing Olympiad-level Problems For Mathematical Reasoning
  In Large Language Models'
authors: Zhao et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 5: Industry Track)'
year: 2025
bibkey: zhao2025promptcot
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.02324'}]
tags: [Prompting, Evaluation, ACL, Datasets, Reinforcement Learning]
---
The ability of large language models to solve complex mathematical problems
has progressed significantly, particularly for tasks requiring advanced
reasoning. However, the scarcity of sufficiently challenging problems,
particularly at the Olympiad level, hinders further advancements. In this work,
we introduce PromptCoT, a novel approach for automatically generating
high-quality Olympiad-level math problems. The proposed method synthesizes
complex problems based on mathematical concepts and the rationale behind
problem construction, emulating the thought processes of experienced problem
designers. We provide a theoretical analysis demonstrating that an optimal
rationale should maximize both the likelihood of rationale generation given the
associated concepts and the likelihood of problem generation conditioned on
both the rationale and the concepts. Our method is evaluated on standard
benchmarks including GSM8K, MATH-500, and AIME2024, where it consistently
outperforms existing problem generation methods. Furthermore, we demonstrate
that PromptCoT exhibits superior data scalability, consistently maintaining
high performance as the dataset size increases, outperforming the baselines.
The implementation is available at https://github.com/zhaoxlpku/PromptCoT.
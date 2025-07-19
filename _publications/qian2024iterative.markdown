---
layout: publication
title: Iterative Experience Refinement Of Software-developing Agents
authors: Qian et al.
conference: IEEE Software
year: 2024
bibkey: qian2024iterative
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.04219'}]
tags: [RAG, Agentic, Tools, Efficiency And Optimization]
---
Autonomous agents powered by large language models (LLMs) show significant
potential for achieving high autonomy in various scenarios such as software
development. Recent research has shown that LLM agents can leverage past
experiences to reduce errors and enhance efficiency. However, the static
experience paradigm, reliant on a fixed collection of past experiences acquired
heuristically, lacks iterative refinement and thus hampers agents'
adaptability. In this paper, we introduce the Iterative Experience Refinement
framework, enabling LLM agents to refine experiences iteratively during task
execution. We propose two fundamental patterns: the successive pattern,
refining based on nearest experiences within a task batch, and the cumulative
pattern, acquiring experiences across all previous task batches. Augmented with
our heuristic experience elimination, the method prioritizes high-quality and
frequently-used experiences, effectively managing the experience space and
enhancing efficiency. Extensive experiments show that while the successive
pattern may yield superior results, the cumulative pattern provides more stable
performance. Moreover, experience elimination facilitates achieving better
performance using just 11.54% of a high-quality subset.
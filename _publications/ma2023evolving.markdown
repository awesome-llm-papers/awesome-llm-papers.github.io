---
layout: publication
title: Evolving Diverse Red-team Language Models In Multi-round Multi-agent Games
authors: Ma et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: ma2023evolving
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.00322'}]
tags: [Prompting, Agentic, CVPR, Efficiency And Optimization, Security, Responsible
    AI]
---
The primary challenge in deploying Large Language Model (LLM) is ensuring its
harmlessness. Red team can identify vulnerabilities by attacking LLM to attain
safety. However, current efforts heavily rely on single-round prompt designs
and unilateral red team optimizations against fixed blue teams. These static
approaches lead to significant reductions in generation diversity, known as the
mode collapse, which makes it difficult to discover the potential risks in the
increasingly complex human-LLM interactions. Here we introduce dynamic Red Team
Game (RTG) to comprehensively analyze the multi-round offensive and defensive
interactions between red team and blue team. Furthermore, we develop a Gamified
Red Team Solver (GRTS) with diversity measures to mitigate mode collapse and
theoretically guarantee the convergence of approximate Nash equilibrium which
results in better strategies for both teams. Empirical results demonstrate that
GRTS explore diverse and implicit attacks to adaptively exploit various LLMs,
surpassing the constraints of specific modes. Insightfully, the geometrical
structure we unveil of the red team task aligns with the spinning top
hypothesis, confirming the necessity of constructing a diverse LLM population
as a promising proxy for heterogeneous human expert red-teamers. This paves the
way for scalable toxicity detection and safe alignment for LLMs.
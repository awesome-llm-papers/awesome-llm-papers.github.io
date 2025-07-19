---
layout: publication
title: One-shot Safety Alignment For Large Language Models Via Optimal Dualization
authors: Huang et al.
conference: Proceedings of the 32nd ACM SIGSOFT International Symposium on Software
  Testing and Analysis
year: 2024
bibkey: huang2024one
citations: 147
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.19544'}]
tags: [Training Techniques, Agentic, Efficiency And Optimization, Reinforcement Learning,
  Responsible AI]
---
The growing safety concerns surrounding large language models raise an urgent
need to align them with diverse human preferences to simultaneously enhance
their helpfulness and safety. A promising approach is to enforce safety
constraints through Reinforcement Learning from Human Feedback (RLHF). For such
constrained RLHF, typical Lagrangian-based primal-dual policy optimization
methods are computationally expensive and often unstable. This paper presents a
perspective of dualization that reduces constrained alignment to an equivalent
unconstrained alignment problem. We do so by pre-optimizing a smooth and convex
dual function that has a closed form. This shortcut eliminates the need for
cumbersome primal-dual policy iterations, greatly reducing the computational
burden and improving training stability. Our strategy leads to two practical
algorithms in model-based and preference-based settings (MoCAN and PeCAN,
respectively). A broad range of experiments demonstrate the effectiveness and
merits of our algorithms.
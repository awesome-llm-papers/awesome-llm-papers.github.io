---
layout: publication
title: Laying The Foundation First? Investigating The Generalization From Atomic Skills
  To Complex Reasoning Tasks
authors: Huang et al.
conference: 2012 IEEE/RSJ International Conference on Intelligent Robots and Systems
year: 2024
bibkey: huang2024laying
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.09479'}]
tags: [RAG, Training Techniques, Tools, IROS, Datasets]
---
Current language models have demonstrated their capability to develop basic
reasoning, but struggle in more complicated reasoning tasks that require a
combination of atomic skills, such as math word problem requiring skills like
arithmetic and unit conversion. Previous methods either do not improve the
inherent atomic skills of models or not attempt to generalize the atomic skills
to complex reasoning tasks. In this paper, we first propose a probing framework
to investigate whether the atomic skill can spontaneously generalize to complex
reasoning tasks. Then, we introduce a hierarchical curriculum learning training
strategy to achieve better skill generalization. In our experiments, we find
that atomic skills can not spontaneously generalize to compositional tasks. By
leveraging hierarchical curriculum learning, we successfully induce
generalization, significantly improve the performance of open-source LMs on
complex reasoning tasks. Promisingly, the skill generalization exhibit
effective in cross-dataset and cross-domain scenarios. Complex reasoning can
also help enhance atomic skills. Our findings offer valuable guidance for
designing better training strategies for complex reasoning tasks.
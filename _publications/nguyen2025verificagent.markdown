---
layout: publication
title: 'Verificagent: Integrating Expert Knowledge And Fact-checked Memory For Robust
  Domain-specific Task Planning'
authors: Nguyen et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: nguyen2025verificagent
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.02539'}]
tags: [Training Techniques, Agentic, Tools, Reinforcement Learning, Fine Tuning]
---
Continual memory augmentation allows computer-use agents (CUAs) to learn from past interactions and refine their task-solving strategies over time. However, unchecked memory accumulation can introduce spurious or hallucinated "learnings" that degrade agent performance, particularly in domain-specific workflows such as productivity software. We present a novel framework, VerificAgent, that effectively manages memory for CUAs through (1) an expert-curated seed of domain knowledge, (2) iterative, trajectory-based memory refinement during training, and (3) a post-hoc fact-checking pass by human experts to sanitize accumulated memory before deployment. On OSWorld productivity tasks, VerificAgent achieves a 111.1% relative improvement in success rate over baseline CUA without any additional fine-tuning.
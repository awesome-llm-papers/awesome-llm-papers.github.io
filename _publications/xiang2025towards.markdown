---
layout: publication
title: 'Towards System 2 Reasoning In Llms: Learning How To Think With Meta Chain-of-though'
authors: Violet Xiang, Charlie Snell, Kanishk Gandhi, Alon Albalak, Anikait Singh,
  Chase Blagden, Duy Phung, Rafael Rafailov, Nathan Lile, Dakota Mahan, Louis Castricato,
  Jan-philipp Franken, Nick Haber, Chelsea Finn
conference: No Venue
year: 2025
bibkey: xiang2025towards
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.04682'}]
tags: ["Training Techniques"]
short_authors: Xiang et al.
---
We propose a novel framework, Meta Chain-of-Thought (Meta-CoT), which extends traditional Chain-of-Thought (CoT) by explicitly modeling the underlying reasoning required to arrive at a particular CoT. We present empirical evidence from state-of-the-art models exhibiting behaviors consistent with in-context search, and explore methods for producing Meta-CoT via process supervision, synthetic data generation, and search algorithms. Finally, we outline a concrete pipeline for training a model to produce Meta-CoTs, incorporating instruction tuning with linearized search traces and reinforcement learning post-training. Finally, we discuss open research questions, including scaling laws, verifier roles, and the potential for discovering novel reasoning algorithms. This work provides a theoretical and practical roadmap to enable Meta-CoT in LLMs, paving the way for more powerful and human-like reasoning in artificial intelligence.

https://huggingface.co/discussions/paper/677f4e1105ab3422540b8a2e
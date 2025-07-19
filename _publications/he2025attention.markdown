---
layout: publication
title: 'Attention Knows Whom To Trust: Attention-based Trust Management For LLM Multi-agent
  Systems'
authors: He et al.
conference: IEEE Access
year: 2025
bibkey: he2025attention
citations: 138
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.02546'}]
tags: [RAG, Attention Mechanism, Prompting, Agentic, Model Architecture, Security]
---
Large Language Model-based Multi-Agent Systems (LLM-MAS) have demonstrated strong capabilities in solving complex tasks but remain vulnerable when agents receive unreliable messages. This vulnerability stems from a fundamental gap: LLM agents treat all incoming messages equally without evaluating their trustworthiness. While some existing studies approach the trustworthiness, they focus on a single type of harmfulness rather than analyze it in a holistic approach from multiple trustworthiness perspectives. In this work, we propose Attention Trust Score (A-Trust), a lightweight, attention-based method for evaluating message trustworthiness. Inspired by human communication literature[1], through systematically analyzing attention behaviors across six orthogonal trust dimensions, we find that certain attention heads in the LLM specialize in detecting specific types of violations. Leveraging these insights, A-Trust directly infers trustworthiness from internal attention patterns without requiring external prompts or verifiers. Building upon A-Trust, we develop a principled and efficient trust management system (TMS) for LLM-MAS, enabling both message-level and agent-level trust assessment. Experiments across diverse multi-agent settings and tasks demonstrate that applying our TMS significantly enhances robustness against malicious inputs.
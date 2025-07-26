---
layout: publication
title: Llm-powered Hierarchical Language Agent For Real-time Human-ai Coordination
authors: Jijia Liu, Chao Yu, Jiaxuan Gao, Yuqing Xie, Qingmin Liao, Yi Wu, Yu Wang
conference: Arxiv
year: 2023
bibkey: liu2023llm
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.15224'}]
tags: ["Agentic", "Applications", "Tools"]
short_authors: Liu et al.
---
AI agents powered by Large Language Models (LLMs) have made significant
advances, enabling them to assist humans in diverse complex tasks and leading
to a revolution in human-AI coordination. LLM-powered agents typically require
invoking LLM APIs and employing artificially designed complex prompts, which
results in high inference latency. While this paradigm works well in scenarios
with minimal interactive demands, such as code generation, it is unsuitable for
highly interactive and real-time applications, such as gaming. Traditional
gaming AI often employs small models or reactive policies, enabling fast
inference but offering limited task completion and interaction abilities. In
this work, we consider Overcooked as our testbed where players could
communicate with natural language and cooperate to serve orders. We propose a
Hierarchical Language Agent (HLA) for human-AI coordination that provides both
strong reasoning abilities while keeping real-time execution. In particular,
HLA adopts a hierarchical framework and comprises three modules: a proficient
LLM, referred to as Slow Mind, for intention reasoning and language
interaction, a lightweight LLM, referred to as Fast Mind, for generating macro
actions, and a reactive policy, referred to as Executor, for transforming macro
actions into atomic actions. Human studies show that HLA outperforms other
baseline agents, including slow-mind-only agents and fast-mind-only agents,
with stronger cooperation abilities, faster responses, and more consistent
language communications.
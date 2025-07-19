---
layout: publication
title: 'Personax: A Recommendation Agent Oriented User Modeling Framework For Long
  Behavior Sequence'
authors: Shi et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: shi2025personax
citations: 166
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.02398'}]
tags: [RAG, Prompting, Agentic, Tools, Evaluation, Efficiency And Optimization, AAAI,
  Datasets]
---
User profile embedded in the prompt template of personalized recommendation agents play a crucial role in shaping their decision-making process. High-quality user profiles are essential for aligning agent behavior with real user interests. Typically, these profiles are constructed by leveraging LLMs for user profile modeling (LLM-UM). However, this process faces several challenges: (1) LLMs struggle with long user behaviors due to context length limitations and performance degradation. (2) Existing methods often extract only partial segments from full historical behavior sequence, inevitably discarding diverse user interests embedded in the omitted content, leading to incomplete modeling and suboptimal profiling. (3) User profiling is often tightly coupled with the inference context, requiring online processing, which introduces significant latency overhead. In this paper, we propose PersonaX, an agent-agnostic LLM-UM framework to address these challenges. It augments downstream recommendation agents to achieve better recommendation performance and inference efficiency. PersonaX (a) segments complete historical behaviors into clustered groups, (b) selects multiple sub behavior sequences (SBS) with a balance of prototypicality and diversity to form a high quality core set, (c) performs offline multi-persona profiling to capture diverse user interests and generate fine grained, cached textual personas, and (d) decouples user profiling from online inference, enabling profile retrieval instead of real time generation. Extensive experiments demonstrate its effectiveness: using only 30 to 50% of behavioral data (sequence length 480), PersonaX enhances AgentCF by 3 to 11% and Agent4Rec by 10 to 50%. As a scalable and model-agnostic LLM-UM solution, PersonaX sets a new benchmark in scalable user modeling.
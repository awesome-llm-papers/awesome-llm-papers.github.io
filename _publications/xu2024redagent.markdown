---
layout: publication
title: 'Redagent: Red Teaming Large Language Models With Context-aware Autonomous
  Language Agent'
authors: Xu et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: xu2024redagent
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.16667'}]
tags: [RAG, EMNLP, GPT, Prompting, Agentic, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning, Security, Applications, Responsible AI]
---
Recently, advanced Large Language Models (LLMs) such as GPT-4 have been
integrated into many real-world applications like Code Copilot. These
applications have significantly expanded the attack surface of LLMs, exposing
them to a variety of threats. Among them, jailbreak attacks that induce toxic
responses through jailbreak prompts have raised critical safety concerns. To
identify these threats, a growing number of red teaming approaches simulate
potential adversarial scenarios by crafting jailbreak prompts to test the
target LLM. However, existing red teaming methods do not consider the unique
vulnerabilities of LLM in different scenarios, making it difficult to adjust
the jailbreak prompts to find context-specific vulnerabilities. Meanwhile,
these methods are limited to refining jailbreak templates using a few mutation
operations, lacking the automation and scalability to adapt to different
scenarios. To enable context-aware and efficient red teaming, we abstract and
model existing attacks into a coherent concept called "jailbreak strategy" and
propose a multi-agent LLM system named RedAgent that leverages these strategies
to generate context-aware jailbreak prompts. By self-reflecting on contextual
feedback in an additional memory buffer, RedAgent continuously learns how to
leverage these strategies to achieve effective jailbreaks in specific contexts.
Extensive experiments demonstrate that our system can jailbreak most black-box
LLMs in just five queries, improving the efficiency of existing red teaming
methods by two times. Additionally, RedAgent can jailbreak customized LLM
applications more efficiently. By generating context-aware jailbreak prompts
towards applications on GPTs, we discover 60 severe vulnerabilities of these
real-world applications with only two queries per vulnerability. We have
reported all found issues and communicated with OpenAI and Meta for bug fixes.
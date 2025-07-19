---
layout: publication
title: 'In-context Defense In Computer Agents: An Empirical Study'
authors: Yang Pei, Ci Hai, Shou Mike Zheng
conference: Archives of General Psychiatry
year: 2025
bibkey: yang2025context
citations: 150
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.09241'}]
tags: [RAG, Agentic, In Context Learning, Security, Multimodal Models, Merging]
---
Computer agents powered by vision-language models (VLMs) have significantly
advanced human-computer interaction, enabling users to perform complex tasks
through natural language instructions. However, these agents are vulnerable to
context deception attacks, an emerging threat where adversaries embed
misleading content into the agent's operational environment, such as a pop-up
window containing deceptive instructions. Existing defenses, such as
instructing agents to ignore deceptive elements, have proven largely
ineffective. As the first systematic study on protecting computer agents, we
introduce textbf\{in-context defense\}, leveraging in-context learning and
chain-of-thought (CoT) reasoning to counter such attacks. Our approach involves
augmenting the agent's context with a small set of carefully curated exemplars
containing both malicious environments and corresponding defensive responses.
These exemplars guide the agent to first perform explicit defensive reasoning
before action planning, reducing susceptibility to deceptive attacks.
Experiments demonstrate the effectiveness of our method, reducing attack
success rates by 91.2% on pop-up window attacks, 74.6% on average on
environment injection attacks, while achieving 100% successful defenses against
distracting advertisements. Our findings highlight that (1) defensive reasoning
must precede action planning for optimal performance, and (2) a minimal number
of exemplars (fewer than three) is sufficient to induce an agent's defensive
behavior.
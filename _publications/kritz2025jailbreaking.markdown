---
layout: publication
title: Jailbreaking To Jailbreak
authors: Kritz et al.
conference: Arxiv
year: 2025
bibkey: kritz2025jailbreaking
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.09638'}]
tags: [Training Techniques, GPT, Prompting, Tools, Model Architecture, Security]
---
Large Language Models (LLMs) can be used to red team other models (e.g. jailbreaking) to elicit harmful contents. While prior works commonly employ open-weight models or private uncensored models for doing jailbreaking, as the refusal-training of strong LLMs (e.g. OpenAI o3) refuse to help jailbreaking, our work turn (almost) any black-box LLMs into attackers. The resulting \\(J_2\\) (jailbreaking-to-jailbreak) attackers can effectively jailbreak the safeguard of target models using various strategies, both created by themselves or from expert human red teamers. In doing so, we show their strong but under-researched jailbreaking capabilities. Our experiments demonstrate that 1) prompts used to create \\(J_2\\) attackers transfer across almost all black-box models; 2) an \\(J_2\\) attacker can jailbreak a copy of itself, and this vulnerability develops rapidly over the past 12 months; 3) reasong models, such as Sonnet-3.7, are strong \\(J_2\\) attackers compared to others. For example, when used against the safeguard of GPT-4o, \\(J_2\\) (Sonnet-3.7) achieves 0.975 attack success rate (ASR), which matches expert human red teamers and surpasses the state-of-the-art algorithm-based attacks. Among \\(J_2\\) attackers, \\(J_2\\) (o3) achieves highest ASR (0.605) against Sonnet-3.5, one of the most robust models.
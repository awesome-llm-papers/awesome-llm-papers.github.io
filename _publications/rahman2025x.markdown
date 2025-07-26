---
layout: publication
title: 'X-teaming: Multi-turn Jailbreaks And Defenses With Adaptive Multi-agents'
authors: Salman Rahman, Liwei Jiang, James Shiffer, Genglin Liu, Sheriff Issaka, Md
  Rizwan Parvez, Hamid Palangi, Kai-wei Chang, Yejin Choi, Saadia Gabriel
conference: No Venue
year: 2025
bibkey: rahman2025x
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.13203'}]
tags: ["Security"]
short_authors: Rahman et al.
---
Multi-turn interactions with language models (LMs) pose critical safety risks, as harmful intent can be strategically spread across exchanges. Yet, the vast majority of prior work has focused on single-turn safety, while adaptability and diversity remain among the key challenges of multi-turn red-teaming. To address these challenges, we present X-Teaming, a scalable framework that systematically explores how seemingly harmless interactions escalate into harmful outcomes and generates corresponding attack scenarios. X-Teaming employs collaborative agents for planning, attack optimization, and verification, achieving state-of-the-art multi-turn jailbreak effectiveness and diversity with success rates up to 98.1% across representative leading open-weight and closed-source models. In particular, X-Teaming achieves a 96.2% attack success rate against the latest Claude 3.7 Sonnet model, which has been considered nearly immune to single-turn attacks. Building on X-Teaming, we introduce XGuard-Train, an open-source multi-turn safety training dataset that is 20x larger than the previous best resource, comprising 30K interactive jailbreaks, designed to enable robust multi-turn safety alignment for LMs. Our work offers essential tools and insights for mitigating sophisticated conversational attacks, advancing the multi-turn safety of LMs.

https://huggingface.co/discussions/paper/68070198c1bd0fc00c7d9101
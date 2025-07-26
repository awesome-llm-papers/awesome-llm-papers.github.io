---
layout: publication
title: 'AGIF: An Adaptive Graph-interactive Framework For Joint Multiple Intent Detection
  And Slot Filling'
authors: Libo Qin, Xiao Xu, Wanxiang Che, Ting Liu
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: qin2020agif
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.10087'}]
tags: ["EMNLP"]
short_authors: Qin et al.
---
In real-world scenarios, users usually have multiple intents in the same
utterance. Unfortunately, most spoken language understanding (SLU) models
either mainly focused on the single intent scenario, or simply incorporated an
overall intent context vector for all tokens, ignoring the fine-grained
multiple intents information integration for token-level slot prediction. In
this paper, we propose an Adaptive Graph-Interactive Framework (AGIF) for joint
multiple intent detection and slot filling, where we introduce an intent-slot
graph interaction layer to model the strong correlation between the slot and
intents. Such an interaction layer is applied to each token adaptively, which
has the advantage to automatically extract the relevant intents information,
making a fine-grained intent information integration for the token-level slot
prediction. Experimental results on three multi-intent datasets show that our
framework obtains substantial improvement and achieves the state-of-the-art
performance. In addition, our framework achieves new state-of-the-art
performance on two single-intent datasets.
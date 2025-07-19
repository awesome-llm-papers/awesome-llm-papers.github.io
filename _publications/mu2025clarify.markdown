---
layout: publication
title: 'CLARIFY: Contrastive Preference Reinforcement Learning For Untangling Ambiguous
  Queries'
authors: Mu et al.
conference: Proceedings of the 31st annual international ACM SIGIR conference on Research
  and development in information retrieval
year: 2025
bibkey: mu2025clarify
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.00388'}]
tags: [Efficiency And Optimization, Agentic, Reinforcement Learning, SIGIR]
---
Preference-based reinforcement learning (PbRL) bypasses explicit reward engineering by inferring reward functions from human preference comparisons, enabling better alignment with human intentions. However, humans often struggle to label a clear preference between similar segments, reducing label efficiency and limiting PbRL's real-world applicability. To address this, we propose an offline PbRL method: Contrastive LeArning for ResolvIng Ambiguous Feedback (CLARIFY), which learns a trajectory embedding space that incorporates preference information, ensuring clearly distinguished segments are spaced apart, thus facilitating the selection of more unambiguous queries. Extensive experiments demonstrate that CLARIFY outperforms baselines in both non-ideal teachers and real human feedback settings. Our approach not only selects more distinguished queries but also learns meaningful trajectory embeddings.
---
layout: publication
title: 'The Invisible Leash: Why RLVR May Not Escape Its Origin'
authors: Fang Wu, Weihao Xuan, Ximing Lu, Zaid Harchaoui, Yejin Choi
conference: No Venue
year: 2025
bibkey: wu2025invisible
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.14843'}]
tags: ["Reinforcement Learning"]
short_authors: Wu et al.
---
Recent advances in large reasoning models highlight Reinforcement Learning with Verifiable Rewards (RLVR) as a promising method for enhancing AI's capabilities, particularly in solving complex logical tasks. However, it remains unclear whether RLVR truly expands a model's reasoning boundary or merely amplifies high-reward outputs that the base model already knows for improved precision. This study presents a theoretical and empirical investigation that provides fresh insights into the potential limits of RLVR. First, we offer a new theoretical perspective that RLVR is constrained by the base model's support-unable to sample solutions with zero initial probability-and operates as a conservative reweighting mechanism that may restrict the discovery of entirely original solutions. We also identify an entropy-reward tradeoff: while RLVR reliably enhances precision, it may progressively narrow exploration and potentially overlook correct yet underrepresented solutions. Extensive empirical experiments validate that while RLVR consistently improves pass@1, the shrinkage of empirical support generally outweighs the expansion of empirical support under larger sampling budgets, failing to recover correct answers that were previously accessible to the base model. Interestingly, we also observe that while RLVR sometimes increases token-level entropy, resulting in greater uncertainty at each generation step, answer-level entropy declines, indicating that these seemingly more uncertain paths ultimately converge onto a smaller set of distinct answers. Taken together, these findings reveal potential limits of RLVR in extending reasoning horizons. Breaking this invisible leash may require future algorithmic innovations such as explicit exploration mechanisms or hybrid strategies that seed probability mass into underrepresented solution regions.

https://huggingface.co/discussions/paper/687f22ed33947f780d9b4b67
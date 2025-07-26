---
layout: publication
title: The Differences Between Direct Alignment Algorithms Are A Blur
authors: Alexey Gorbatovski, Boris Shaposhnikov, Viacheslav Sinii, Alexey Malakhov,
  Daniil Gavrilov
conference: No Venue
year: 2025
bibkey: gorbatovski2025differences
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.01237'}]
tags: ["Efficiency", "Evaluation", "Fine-Tuning", "Reinforcement Learning"]
short_authors: Gorbatovski et al.
---
Direct Alignment Algorithms (DAAs) simplify language model alignment by replacing reinforcement learning (RL) and reward modeling (RM) in Reinforcement Learning from Human Feedback (RLHF) with direct policy optimization. DAAs can be classified by their ranking losses (pairwise vs. pointwise), by the rewards used in those losses (e.g., likelihood ratios of policy and reference policy, or odds ratios), or by whether a Supervised Fine-Tuning (SFT) phase is required (two-stage vs. one-stage). We first show that one-stage methods underperform two-stage methods. To address this, we incorporate an explicit SFT phase and introduce the beta parameter, controlling the strength of preference optimization, into single-stage ORPO and ASFT. These modifications improve their performance in Alpaca Eval 2 by +3.46 (ORPO) and +8.27 (ASFT), matching two-stage methods like DPO. Further analysis reveals that the key factor is whether the approach uses pairwise or pointwise objectives, rather than the specific implicit reward or loss function. These results highlight the importance of careful evaluation to avoid premature claims of performance gains or overall superiority in alignment algorithms.

https://huggingface.co/discussions/paper/67a1c1438747511e7b9a19ae
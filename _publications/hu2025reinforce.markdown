---
layout: publication
title: 'REINFORCE++: A Simple And Efficient Approach For Aligning Large Language Models'
authors: Jian Hu
conference: No Venue
year: 2025
bibkey: hu2025reinforce
additional_links: [{name: Code, url: 'https://github.com/OpenRLHF/OpenRLHF'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2501.03262'}]
tags: ["Efficiency", "Reinforcement Learning", "Training Techniques"]
short_authors: Jian Hu
---
Reinforcement Learning from Human Feedback (RLHF) has emerged as a critical approach for aligning large language models with human preferences, witnessing rapid algorithmic evolution through methods such as Proximal Policy Optimization (PPO), Direct Preference Optimization (DPO), REINFORCE Leave One-Out (RLOO), ReMax, and Group Relative Policy Optimization (GRPO). We present REINFORCE++, an enhanced variant of the classical REINFORCE algorithm that incorporates key optimization techniques from PPO while eliminating the need for a critic network. REINFORCE++ achieves three primary objectives: (1) simplicity (2) enhanced training stability, and (3) reduced computational overhead. Through extensive empirical evaluation, we demonstrate that REINFORCE++ exhibits superior stability compared to GRPO and achieves greater computational efficiency than PPO while maintaining comparable performance. The implementation is available at https://github.com/OpenRLHF/OpenRLHF.

https://huggingface.co/discussions/paper/677e18a77edb3025daa99e4f
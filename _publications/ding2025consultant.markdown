---
layout: publication
title: 'Consultant Decoding: Yet Another Synergistic Mechanism'
authors: Ding et al.
conference: Combustion and Flame
year: 2025
bibkey: ding2025consultant
citations: 177
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.02391'}]
tags: [Model Architecture, Efficiency And Optimization, Reinforcement Learning, Attention
    Mechanism]
---
The synergistic mechanism based on Speculative Decoding (SD) has garnered considerable attention as a simple yet effective approach for accelerating the inference of large language models (LLMs). Nonetheless, the high rejection rates require repeated LLMs calls to validate draft tokens, undermining the overall efficiency gain of SD. In this work, we revisit existing verification mechanisms and propose a novel synergetic mechanism Consultant Decoding (CD). Unlike SD, which relies on a metric derived from importance sampling for verification, CD verifies candidate drafts using token-level likelihoods computed solely by the LLM. CD achieves up to a 2.5-fold increase in inference speed compared to the target model, while maintaining comparable generation quality (around 100% of the target model's performance). Interestingly, this is achieved by combining models whose parameter sizes differ by two orders of magnitude. In addition, CD reduces the call frequency of the large target model to below 10%, particularly in more demanding tasks. CD's performance was even found to surpass that of the large target model, which theoretically represents the upper bound for speculative decoding.
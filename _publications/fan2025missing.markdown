---
layout: publication
title: 'Missing Premise Exacerbates Overthinking: Are Reasoning Models Losing Critical
  Thinking Skill?'
authors: Chenrui Fan, Ming Li, Lichao Sun, Tianyi Zhou
conference: No Venue
year: 2025
bibkey: fan2025missing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.06514'}]
tags: ["Datasets", "Efficiency", "Reinforcement Learning", "Training Techniques"]
short_authors: Fan et al.
---
We find that the response length of reasoning LLMs, whether trained by reinforcement learning or supervised learning, drastically increases for ill-posed questions with missing premises (MiP), ending up with redundant and ineffective thinking. This newly introduced scenario exacerbates the general overthinking issue to a large extent, which we name as the MiP-Overthinking. Such failures are against the ``test-time scaling law'' but have been widely observed on multiple datasets we curated with MiP, indicating the harm of cheap overthinking and a lack of critical thinking. Surprisingly, LLMs not specifically trained for reasoning exhibit much better performance on the MiP scenario, producing much shorter responses that quickly identify ill-posed queries. This implies a critical flaw of the current training recipe for reasoning LLMs, which does not encourage efficient thinking adequately, leading to the abuse of thinking patterns. To further investigate the reasons behind such failures, we conduct fine-grained analyses of the reasoning length, overthinking patterns, and location of critical thinking on different types of LLMs. Moreover, our extended ablation study reveals that the overthinking is contagious through the distillation of reasoning models' responses. These results improve the understanding of overthinking and shed novel insights into mitigating the problem.

https://huggingface.co/discussions/paper/67f72e943eacf8888816f3fa
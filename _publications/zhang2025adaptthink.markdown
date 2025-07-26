---
layout: publication
title: 'Adaptthink: Reasoning Models Can Learn When To Think'
authors: Jiajie Zhang, Nianyi Lin, Lei Hou, Ling Feng, Juanzi Li
conference: No Venue
year: 2025
bibkey: zhang2025adaptthink
additional_links: [{name: Code, url: 'https://github.com/THU-KEG/AdaptThink'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/682be3e53ba4cfbca886a551'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.13417'}]
tags: ["Datasets", "Efficiency", "Has Code", "Reinforcement Learning", "Training Techniques"]
short_authors: Zhang et al.
---
Recently, large reasoning models have achieved impressive performance on various tasks by employing human-like deep thinking. However, the lengthy thinking process substantially increases inference overhead, making efficiency a critical bottleneck. In this work, we first demonstrate that NoThinking, which prompts the reasoning model to skip thinking and directly generate the final solution, is a better choice for relatively simple tasks in terms of both performance and efficiency. Motivated by this, we propose AdaptThink, a novel RL algorithm to teach reasoning models to choose the optimal thinking mode adaptively based on problem difficulty. Specifically, AdaptThink features two core components: (1) a constrained optimization objective that encourages the model to choose NoThinking while maintaining the overall performance; (2) an importance sampling strategy that balances Thinking and NoThinking samples during on-policy training, thereby enabling cold start and allowing the model to explore and exploit both thinking modes throughout the training process. Our experiments indicate that AdaptThink significantly reduces the inference costs while further enhancing performance. Notably, on three math datasets, AdaptThink reduces the average response length of DeepSeek-R1-Distill-Qwen-1.5B by 53% and improves its accuracy by 2.4%, highlighting the promise of adaptive thinking-mode selection for optimizing the balance between reasoning quality and efficiency. Our codes and models are available at https://github.com/THU-KEG/AdaptThink.

https://huggingface.co/discussions/paper/682be3e53ba4cfbca886a551
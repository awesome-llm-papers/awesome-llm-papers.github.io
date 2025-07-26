---
layout: publication
title: 'Thinkless: LLM Learns When To Think'
authors: Gongfan Fang, Xinyin Ma, Xinchao Wang
conference: No Venue
year: 2025
bibkey: fang2025thinkless
additional_links: [{name: Code, url: 'https://github.com/VainF/Thinkless'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/682bf33309ce6055262b43fd'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.13379'}]
tags: ["Has Code", "Tools", "Training Techniques"]
short_authors: Gongfan Fang, Xinyin Ma, Xinchao Wang
---
Reasoning Language Models, capable of extended chain-of-thought reasoning, have demonstrated remarkable performance on tasks requiring complex logical inference. However, applying elaborate reasoning for all queries often results in substantial computational inefficiencies, particularly when many problems admit straightforward solutions. This motivates an open question: Can LLMs learn when to think? To answer this, we propose Thinkless, a learnable framework that empowers an LLM to adaptively select between short-form and long-form reasoning, based on both task complexity and the model's ability. Thinkless is trained under a reinforcement learning paradigm and employs two control tokens, <short> for concise responses and <think> for detailed reasoning. At the core of our method is a Decoupled Group Relative Policy Optimization (DeGRPO) algorithm, which decomposes the learning objective of hybrid reasoning into two components: (1) a control token loss that governs the selection of the reasoning mode, and (2) a response loss that improves the accuracy of the generated answers. This decoupled formulation enables fine-grained control over the contributions of each objective, stabilizing training and effectively preventing collapse observed in vanilla GRPO. Empirically, on several benchmarks such as Minerva Algebra, MATH-500, and GSM8K, Thinkless is able to reduce the usage of long-chain thinking by 50% - 90%, significantly improving the efficiency of Reasoning Language Models. The code is available at https://github.com/VainF/Thinkless

https://huggingface.co/discussions/paper/682bf33309ce6055262b43fd
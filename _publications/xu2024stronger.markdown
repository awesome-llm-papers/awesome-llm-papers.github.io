---
layout: publication
title: Stronger Models Are NOT Stronger Teachers For Instruction Tuning
authors: Zhangchen Xu, Fengqing Jiang, Luyao Niu, Bill Yuchen Lin, Radha Poovendran
conference: No Venue
year: 2024
bibkey: xu2024stronger
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.07133'}]
tags: ["Datasets", "Evaluation", "Reinforcement Learning"]
short_authors: Xu et al.
---
Instruction tuning has been widely adopted to ensure large language models (LLMs) follow user instructions effectively. The resulting instruction-following capabilities of LLMs heavily rely on the instruction datasets used for tuning. Recently, synthetic instruction datasets have emerged as an economically viable solution to provide LLMs diverse and high-quality instructions. However, existing approaches typically assume that larger or stronger models are stronger teachers for instruction tuning, and hence simply adopt these models as response generators to the synthetic instructions. In this paper, we challenge this commonly-adopted assumption. Our extensive experiments across five base models and twenty response generators reveal that larger and stronger models are not necessarily stronger teachers of smaller models. We refer to this phenomenon as the Larger Models' Paradox. We observe that existing metrics cannot precisely predict the effectiveness of response generators since they ignore the compatibility between teachers and base models being fine-tuned. We thus develop a novel metric, named as Compatibility-Adjusted Reward (CAR) to measure the effectiveness of response generators. Our experiments across five base models demonstrate that CAR outperforms almost all baselines.

https://huggingface.co/discussions/paper/6734679bd3521b36246eb7d0
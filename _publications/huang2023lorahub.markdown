---
layout: publication
title: 'Lorahub: Efficient Cross-task Generalization Via Dynamic Lora Composition'
authors: Chengsong Huang, Qian Liu, Bill Yuchen Lin, Tianyu Pang, Chao Du, Min Lin
conference: No Venue
year: 2023
bibkey: huang2023lorahub
additional_links: [{name: Code, url: 'https://github.com/sail-sg/lorahub'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/64c086e75e03515457f6906d'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2307.13269'}]
tags: ["Has Code", "Tools"]
short_authors: Huang et al.
---
Low-rank adaptations (LoRA) are often employed to fine-tune large language models (LLMs) for new tasks. This paper investigates LoRA composability for cross-task generalization and introduces LoraHub, a strategic framework devised for the purposive assembly of LoRA modules trained on diverse given tasks, with the objective of achieving adaptable performance on unseen tasks. With just a few examples from a novel task, LoraHub enables the fluid combination of multiple LoRA modules, eradicating the need for human expertise. Notably, the composition requires neither additional model parameters nor gradients. Our empirical results, derived from the Big-Bench Hard (BBH) benchmark, suggest that LoraHub can effectively mimic the performance of in-context learning in few-shot scenarios, excluding the necessity of in-context examples alongside each inference input. A significant contribution of our research is the fostering of a community for LoRA, where users can share their trained LoRA modules, thereby facilitating their application to new tasks. We anticipate this resource will widen access to and spur advancements in general intelligence as well as LLMs in production. Code will be available at https://github.com/sail-sg/lorahub.

https://huggingface.co/discussions/paper/64c086e75e03515457f6906d
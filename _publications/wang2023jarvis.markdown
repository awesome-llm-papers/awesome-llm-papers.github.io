---
layout: publication
title: 'JARVIS-1: Open-world Multi-task Agents With Memory-augmented Multimodal Language
  Models'
authors: Zihao Wang, Shaofei Cai, Anji Liu, Yonggang Jin, Jinbing Hou, Bowei Zhang,
  Haowei Lin, Zhaofeng He, Zilong Zheng, Yaodong Yang, Xiaojian Ma, Yitao Liang
conference: No Venue
year: 2023
bibkey: wang2023jarvis
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2311.05997'}]
tags: ["Agentic"]
short_authors: Wang et al.
---
Achieving human-like planning and control with multimodal observations in an open world is a key milestone for more functional generalist agents. Existing approaches can handle certain long-horizon tasks in an open world. However, they still struggle when the number of open-world tasks could potentially be infinite and lack the capability to progressively enhance task completion as game time progresses. We introduce JARVIS-1, an open-world agent that can perceive multimodal input (visual observations and human instructions), generate sophisticated plans, and perform embodied control, all within the popular yet challenging open-world Minecraft universe. Specifically, we develop JARVIS-1 on top of pre-trained multimodal language models, which map visual observations and textual instructions to plans. The plans will be ultimately dispatched to the goal-conditioned controllers. We outfit JARVIS-1 with a multimodal memory, which facilitates planning using both pre-trained knowledge and its actual game survival experiences. In our experiments, JARVIS-1 exhibits nearly perfect performances across over 200 varying tasks from the Minecraft Universe Benchmark, ranging from entry to intermediate levels. JARVIS-1 has achieved a completion rate of 12.5% in the long-horizon diamond pickaxe task. This represents a significant increase up to 5 times compared to previous records. Furthermore, we show that JARVIS-1 is able to self-improve following a life-long learning paradigm thanks to multimodal memory, sparking a more general intelligence and improved autonomy. The project page is available at https://craftjarvis-jarvis1.github.io.

https://huggingface.co/discussions/paper/65519bd032f278f503b3378b
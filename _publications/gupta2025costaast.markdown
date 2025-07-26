---
layout: publication
title: 'Costaast: Cost-sensitive Toolpath Agent For Multi-turn Image Editing'
authors: Advait Gupta, Nandakiran Velaga, Dang Nguyen, Tianyi Zhou
conference: No Venue
year: 2025
bibkey: gupta2025costaast
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.10613'}]
tags: ["Tools"]
short_authors: Gupta et al.
---
Text-to-image models like stable diffusion and DALLE-3 still struggle with multi-turn image editing. We decompose such a task as an agentic workflow (path) of tool use that addresses a sequence of subtasks by AI tools of varying costs. Conventional search algorithms require expensive exploration to find tool paths. While large language models (LLMs) possess prior knowledge of subtask planning, they may lack accurate estimations of capabilities and costs of tools to determine which to apply in each subtask. Can we combine the strengths of both LLMs and graph search to find cost-efficient tool paths? We propose a three-stage approach "CoSTA*" that leverages LLMs to create a subtask tree, which helps prune a graph of AI tools for the given task, and then conducts A* search on the small subgraph to find a tool path. To better balance the total cost and quality, CoSTA* combines both metrics of each tool on every subtask to guide the A* search. Each subtask's output is then evaluated by a vision-language model (VLM), where a failure will trigger an update of the tool's cost and quality on the subtask. Hence, the A* search can recover from failures quickly to explore other paths. Moreover, CoSTA* can automatically switch between modalities across subtasks for a better cost-quality trade-off. We build a novel benchmark of challenging multi-turn image editing, on which CoSTA* outperforms state-of-the-art image-editing models or agents in terms of both cost and quality, and performs versatile trade-offs upon user preference.

https://huggingface.co/discussions/paper/67d393cf336d57afb21bc0db
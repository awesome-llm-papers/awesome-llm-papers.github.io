---
layout: publication
title: 'The Danger Of Overthinking: Examining The Reasoning-action Dilemma In Agentic
  Tasks'
authors: Alejandro Cuadron, Dacheng Li, Wenjie Ma, Xingyao Wang, Yichuan Wang, Siyuan
  Zhuang, Shu Liu, Luis Gaspar Schroeder, Tian Xia, Huanzhi Mao, Nicholas Thumiger,
  Aditya Desai, Ion Stoica, Ana Klimovic, Graham Neubig, Joseph E. Gonzalez
conference: No Venue
year: 2025
bibkey: cuadron2025danger
additional_links: [{name: Code, url: 'https://github.com/AlexCuadron/Overthinking'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67b078cc1c879c0cbb785dbb'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.08235'}]
tags: ["Agentic"]
short_authors: Cuadron et al.
---
Large Reasoning Models (LRMs) represent a breakthrough in AI problem-solving capabilities, but their effectiveness in interactive environments can be limited. This paper introduces and analyzes overthinking in LRMs. A phenomenon where models favor extended internal reasoning chains over environmental interaction. Through experiments on software engineering tasks using SWE Bench Verified, we observe three recurring patterns: Analysis Paralysis, Rogue Actions, and Premature Disengagement. We propose a framework to study these behaviors, which correlates with human expert assessments, and analyze 4018 trajectories. We observe that higher overthinking scores correlate with decreased performance, with reasoning models exhibiting stronger tendencies toward overthinking compared to non-reasoning models. Our analysis reveals that simple efforts to mitigate overthinking in agentic environments, such as selecting the solution with the lower overthinking score, can improve model performance by almost 30% while reducing computational costs by 43%. These results suggest that mitigating overthinking has strong practical implications. We suggest that by leveraging native function-calling capabilities and selective reinforcement learning overthinking tendencies could be mitigated. We also open-source our evaluation framework and dataset to facilitate research in this direction at https://github.com/AlexCuadron/Overthinking.

https://huggingface.co/discussions/paper/67b078cc1c879c0cbb785dbb
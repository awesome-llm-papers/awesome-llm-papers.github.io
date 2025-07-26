---
layout: publication
title: Great Models Think Alike And This Undermines AI Oversight
authors: Shashwat Goel, Joschka Struber, Ilze Amanda Auzina, Karuna K Chandra, Ponnurangam
  Kumaraguru, Douwe Kiela, Ameya Prabhu, Matthias Bethge, Jonas Geiping
conference: No Venue
year: 2025
bibkey: goel2025great
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67a5b9137897c8f540615673'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.04313'}]
tags: ["Training Techniques"]
short_authors: Goel et al.
---
As Language Model (LM) capabilities advance, evaluating and supervising them at scale is getting harder for humans. There is hope that other language models can automate both these tasks, which we refer to as "AI Oversight". We study how model similarity affects both aspects of AI oversight by proposing a probabilistic metric for LM similarity based on overlap in model mistakes. Using this metric, we first show that LLM-as-a-judge scores favor models similar to the judge, generalizing recent self-preference results. Then, we study training on LM annotations, and find complementary knowledge between the weak supervisor and strong student model plays a crucial role in gains from "weak-to-strong generalization". As model capabilities increase, it becomes harder to find their mistakes, and we might defer more to AI oversight. However, we observe a concerning trend -- model mistakes are becoming more similar with increasing capabilities, pointing to risks from correlated failures. Our work underscores the importance of reporting and correcting for model similarity, especially in the emerging paradigm of AI oversight.

https://huggingface.co/discussions/paper/67a5b9137897c8f540615673
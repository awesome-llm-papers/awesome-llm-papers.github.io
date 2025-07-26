---
layout: publication
title: 'Skeleton-of-thought: Large Language Models Can Do Parallel Decoding'
authors: Xuefei Ning, Zinan Lin, Zixuan Zhou, Huazhong Yang, Yu Wang
conference: No Venue
year: 2023
bibkey: ning2023skeleton
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2307.15337'}]
tags: ["Efficiency"]
short_authors: Ning et al.
---
This work aims at decreasing the end-to-end generation latency of large language models (LLMs). One of the major causes of the high generation latency is the sequential decoding approach adopted by almost all state-of-the-art LLMs. In this work, motivated by the thinking and writing process of humans, we propose "Skeleton-of-Thought" (SoT), which guides LLMs to first generate the skeleton of the answer, and then conducts parallel API calls or batched decoding to complete the contents of each skeleton point in parallel. Not only does SoT provide considerable speed-up (up to 2.39x across 11 different LLMs), but it can also potentially improve the answer quality on several question categories in terms of diversity and relevance. SoT is an initial attempt at data-centric optimization for efficiency, and reveal the potential of pushing LLMs to think more like a human for answer quality.

https://huggingface.co/discussions/paper/64c75426720d494bb2aa1b1e
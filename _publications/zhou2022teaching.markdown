---
layout: publication
title: Teaching Algorithmic Reasoning Via In-context Learning
authors: Hattie Zhou et al.
conference: Arxiv
year: 2022
citations: 21
bibkey: zhou2022teaching
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.09066'}]
tags: [Tools, Prompting, In-Context Learning]
---
Large language models (LLMs) have shown increasing in-context learning
capabilities through scaling up model and data size. Despite this progress,
LLMs are still unable to solve algorithmic reasoning problems. While providing
a rationale with the final answer has led to further improvements in multi-step
reasoning problems, Anil et al. 2022 showed that even simple algorithmic
reasoning tasks such as parity are far from solved. In this work, we identify
and study four key stages for successfully teaching algorithmic reasoning to
LLMs: (1) formulating algorithms as skills, (2) teaching multiple skills
simultaneously (skill accumulation), (3) teaching how to combine skills (skill
composition) and (4) teaching how to use skills as tools. We show that it is
possible to teach algorithmic reasoning to LLMs via in-context learning, which
we refer to as algorithmic prompting. We evaluate our approach on a variety of
arithmetic and quantitative reasoning tasks, and demonstrate significant boosts
in performance over existing prompting techniques. In particular, for long
parity, addition, multiplication and subtraction, we achieve an error reduction
of approximately 10x, 9x, 5x and 2x respectively compared to the best available
baselines.
---
layout: publication
title: 'Cos: Chain-of-shot Prompting For Long Video Understanding'
authors: Hu et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: hu2025cos
citations: 186
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.06428'}]
tags: [Prompting, Datasets]
---
Multi-modal Large Language Models (MLLMs) struggle with long videos due to
the need for excessive visual tokens. These tokens exceed massively the context
length of MLLMs, resulting in filled by redundant task-irrelevant shots. How to
select shots is an unsolved critical problem: sparse sampling risks missing key
details, while exhaustive sampling overwhelms the model with irrelevant
content, leading to video misunderstanding. To solve this problem, we propose
Chain-of-Shot prompting (CoS). The key idea is to frame shot selection as
test-time visual prompt optimisation, choosing shots adaptive to video
understanding semantic task by optimising shots-task alignment. CoS has two key
parts: (1) a binary video summary mechanism that performs pseudo temporal
grounding, discovering a binary coding to identify task-relevant shots, and (2)
a video co-reasoning module that deploys the binary coding to pair (learning to
align) task-relevant positive shots with irrelevant negative shots. It embeds
the optimised shot selections into the original video, facilitating a focus on
relevant context to optimize long video understanding. Experiments across three
baselines and five datasets demonstrate the effectiveness and adaptability of
CoS. Code given in https://lwpyh.github.io/CoS.
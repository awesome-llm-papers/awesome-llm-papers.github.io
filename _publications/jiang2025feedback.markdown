---
layout: publication
title: 'Feedback Friction: Llms Struggle To Fully Incorporate External Feedback'
authors: Dongwei Jiang, Alvin Zhang, Andrew Wang, Nicholas Andrews, Daniel Khashabi
conference: No Venue
year: 2025
bibkey: jiang2025feedback
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.11930'}]
tags: []
short_authors: Jiang et al.
---
Recent studies have shown LLMs possess some ability to improve their responses when given external feedback. However, it remains unclear how effectively and thoroughly these models can incorporate extrinsic feedback. In an ideal scenario, if LLMs receive near-perfect and complete feedback, we would expect them to fully integrate the feedback and change their incorrect answers to correct ones. In this paper, we systematically investigate LLMs' ability to incorporate feedback by designing a controlled experimental environment. For each problem, a solver model attempts a solution, then a feedback generator with access to near-complete ground-truth answers produces targeted feedback, after which the solver tries again. We evaluate this pipeline across a diverse range of tasks, including math reasoning, knowledge reasoning, scientific reasoning, and general multi-domain evaluations with state-of-the-art language models including Claude 3.7 (with and without extended thinking). Surprisingly, even under these near-ideal conditions, solver models consistently show resistance to feedback, a limitation that we term FEEDBACK FRICTION. To mitigate this limitation, we experiment with sampling-based strategies like progressive temperature increases and explicit rejection of previously attempted incorrect answers, which yield improvements but still fail to help models achieve target performance. We also perform a rigorous exploration of potential causes of FEEDBACK FRICTION, ruling out factors such as model overconfidence and data familiarity. We hope that highlighting this issue in LLMs and ruling out several apparent causes will help future research in self-improvement.

https://huggingface.co/discussions/paper/684fbab760b4a34dbe007b19
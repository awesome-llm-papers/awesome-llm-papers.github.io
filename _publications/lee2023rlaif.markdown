---
layout: publication
title: 'RLAIF: Scaling Reinforcement Learning From Human Feedback With AI Feedback'
authors: Harrison Lee, Samrat Phatale, Hassan Mansoor, Kellie Lu, Thomas Mesnard,
  Colton Bishop, Victor Carbune, Abhinav Rastogi
conference: No Venue
year: 2023
bibkey: lee2023rlaif
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.00267'}]
tags: ["Reinforcement Learning"]
short_authors: Lee et al.
---
Reinforcement learning from human feedback (RLHF) is effective at aligning large language models (LLMs) to human preferences, but gathering high quality human preference labels is a key bottleneck. We conduct a head-to-head comparison of RLHF vs. RL from AI Feedback (RLAIF) - a technique where preferences are labeled by an off-the-shelf LLM in lieu of humans, and we find that they result in similar improvements. On the task of summarization, human evaluators prefer generations from both RLAIF and RLHF over a baseline supervised fine-tuned model in ~70% of cases. Furthermore, when asked to rate RLAIF vs. RLHF summaries, humans prefer both at equal rates. These results suggest that RLAIF can yield human-level performance, offering a potential solution to the scalability limitations of RLHF.

https://huggingface.co/discussions/paper/64f529842335edf7651f824d
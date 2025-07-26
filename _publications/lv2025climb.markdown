---
layout: publication
title: 'The Climb Carves Wisdom Deeper Than The Summit: On The Noisy Rewards In Learning
  To Reason'
authors: Ang Lv, Ruobing Xie, Xingwu Sun, Zhanhui Kang, Rui Yan
conference: No Venue
year: 2025
bibkey: lv2025climb
additional_links: [{name: Code, url: 'https://github.com/trestad/Noisy-Rewards-in-Learning-to-Reason'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6838bb2a2b382ba50bdcde1b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.22653'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Lv et al.
---
Recent studies on post-training large language models (LLMs) for reasoning through reinforcement learning (RL) typically focus on tasks that can be accurately verified and rewarded, such as solving math problems. In contrast, our research investigates the impact of reward noise, a more practical consideration for real-world scenarios involving the post-training of LLMs using reward models. We found that LLMs demonstrate strong robustness to substantial reward noise. For example, manually flipping 40% of the reward function's outputs in math tasks still allows a Qwen-2.5-7B model to achieve rapid convergence, improving its performance on math tasks from 5% to 72%, compared to the 75% accuracy achieved by a model trained with noiseless rewards. Surprisingly, by only rewarding the appearance of key reasoning phrases (namely reasoning pattern reward, RPR), such as ``first, I need to''-without verifying the correctness of answers, the model achieved peak downstream performance (over 70% accuracy for Qwen-2.5-7B) comparable to models trained with strict correctness verification and accurate rewards. Recognizing the importance of the reasoning process over the final results, we combined RPR with noisy reward models. RPR helped calibrate the noisy reward models, mitigating potential false negatives and enhancing the LLM's performance on open-ended tasks. These findings suggest the importance of improving models' foundational abilities during the pre-training phase while providing insights for advancing post-training techniques. Our code and scripts are available at https://github.com/trestad/Noisy-Rewards-in-Learning-to-Reason.

https://huggingface.co/discussions/paper/6838bb2a2b382ba50bdcde1b
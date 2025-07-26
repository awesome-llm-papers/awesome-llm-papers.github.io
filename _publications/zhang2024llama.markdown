---
layout: publication
title: 'Llama-berry: Pairwise Optimization For O1-like Olympiad-level Mathematical
  Reasoning'
authors: di Zhang, Jianbo Wu, Jingdi Lei, Tong Che, Jiatong Li, Tong Xie, Xiaoshui
  Huang, Shufei Zhang, Marco Pavone, Yuqiang Li, Wanli Ouyang, Dongzhan Zhou
conference: No Venue
year: 2024
bibkey: zhang2024llama
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.02884'}]
tags: ["Efficiency", "Reinforcement Learning", "Tools"]
short_authors: Zhang et al.
---
This paper presents an advanced mathematical problem-solving framework, LLaMA-Berry, for enhancing the mathematical reasoning ability of Large Language Models (LLMs). The framework combines Monte Carlo Tree Search (MCTS) with iterative Self-Refine to optimize the reasoning path and utilizes a pairwise reward model to evaluate different paths globally. By leveraging the self-critic and rewriting capabilities of LLMs, Self-Refine applied to MCTS (SR-MCTS) overcomes the inefficiencies and limitations of conventional step-wise and greedy search algorithms by fostering a more efficient exploration of solution spaces. Pairwise Preference Reward Model~(PPRM), inspired by Reinforcement Learning from Human Feedback (RLHF), is then used to model pairwise preferences between solutions, utilizing an Enhanced Borda Count (EBC) method to synthesize these preferences into a global ranking score to find better answers. This approach addresses the challenges of scoring variability and non-independent distributions in mathematical reasoning tasks. The framework has been tested on general and advanced benchmarks, showing superior performance in terms of search efficiency and problem-solving capability compared to existing methods like ToT and rStar, particularly in complex Olympiad-level benchmarks, including GPQA, AIME24 and AMC23.

https://huggingface.co/discussions/paper/6704ec6b0fbef97683f158a2
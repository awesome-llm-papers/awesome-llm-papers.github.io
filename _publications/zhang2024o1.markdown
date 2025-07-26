---
layout: publication
title: 'O1-coder: An O1 Replication For Coding'
authors: Yuxiang Zhang, Shangxi Wu, Yuqi Yang, Jiangming Shu, Jinlin Xiao, Chao Kong,
  Jitao Sang
conference: No Venue
year: 2024
bibkey: zhang2024o1
additional_links: [{name: Code, url: 'https://github.com/ADaM-BJTU/O1-CODER'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/674e99023209f1fbb76bbf06'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2412.00154'}]
tags: ["Applications", "Datasets", "Fine-Tuning", "Has Code", "Reinforcement Learning", "Tools", "Training Techniques"]
short_authors: Zhang et al.
---
The technical report introduces O1-CODER, an attempt to replicate OpenAI's o1 model with a focus on coding tasks. It integrates reinforcement learning (RL) and Monte Carlo Tree Search (MCTS) to enhance the model's System-2 thinking capabilities. The framework includes training a Test Case Generator (TCG) for standardized code testing, using MCTS to generate code data with reasoning processes, and iteratively fine-tuning the policy model to initially produce pseudocode, followed by the generation of the full code. The report also addresses the opportunities and challenges in deploying o1-like models in real-world applications, suggesting transitioning to the System-2 paradigm and highlighting the imperative for environment state updates. Updated model progress and experimental results will be reported in subsequent versions. All source code, curated datasets, as well as the derived models will be disclosed at https://github.com/ADaM-BJTU/O1-CODER .

https://huggingface.co/discussions/paper/674e99023209f1fbb76bbf06
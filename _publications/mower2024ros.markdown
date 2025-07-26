---
layout: publication
title: 'ROS-LLM: A ROS Framework For Embodied AI With Task Feedback And Structured
  Reasoning'
authors: Christopher E. Mower, Yuhui Wan, Hongzhan Yu, Antoine Grosnit, Jonas Gonzalez-billandon,
  Matthieu Zimmer, Jinlong Wang, Xinyu Zhang, Yao Zhao, Anbang Zhai, Puze Liu, Davide
  Tateo, Cesar Cadena, Marco Hutter, Jan Peters, Guangjian Tian, Yuzheng Zhuang, Kun
  Shao, Xingyue Quan, Jianye Hao, Jun Wang, Haitham Bou-ammar
conference: No Venue
year: 2024
bibkey: mower2024ros
additional_links: [{name: Code, url: 'https://github.com/huawei-noah/HEBO/tree/master/ROSLLM'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6684021a0e8e112087145df7'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.19741'}]
tags: ["Agentic", "Has Code", "Tools"]
short_authors: Mower et al.
---
We present a framework for intuitive robot programming by non-experts, leveraging natural language prompts and contextual information from the Robot Operating System (ROS). Our system integrates large language models (LLMs), enabling non-experts to articulate task requirements to the system through a chat interface. Key features of the framework include: integration of ROS with an AI agent connected to a plethora of open-source and commercial LLMs, automatic extraction of a behavior from the LLM output and execution of ROS actions/services, support for three behavior modes (sequence, behavior tree, state machine), imitation learning for adding new robot actions to the library of possible actions, and LLM reflection via human and environment feedback. Extensive experiments validate the framework, showcasing robustness, scalability, and versatility in diverse scenarios, including long-horizon tasks, tabletop rearrangements, and remote supervisory control. To facilitate the adoption of our framework and support the reproduction of our results, we have made our code open-source. You can access it at: https://github.com/huawei-noah/HEBO/tree/master/ROSLLM.

https://huggingface.co/discussions/paper/6684021a0e8e112087145df7
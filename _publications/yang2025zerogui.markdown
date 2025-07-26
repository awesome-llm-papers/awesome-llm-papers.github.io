---
layout: publication
title: 'Zerogui: Automating Online GUI Learning At Zero Human Cost'
authors: Chenyu Yang, Shiqian Su, Shi Liu, Xuan Dong, Yue Yu, Weijie Su, Xuehui Wang,
  Zhaoyang Liu, Jinguo Zhu, Hao Li, Wenhai Wang, Yu Qiao, Xizhou Zhu, Jifeng Dai
conference: No Venue
year: 2025
bibkey: yang2025zerogui
additional_links: [{name: Code, url: 'https://github.com/OpenGVLab/ZeroGUI'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/68391354d8c153d346e1de1a'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.23762'}]
tags: ["Tools"]
short_authors: Yang et al.
---
The rapid advancement of large Vision-Language Models (VLMs) has propelled the development of pure-vision-based GUI Agents, capable of perceiving and operating Graphical User Interfaces (GUI) to autonomously fulfill user instructions. However, existing approaches usually adopt an offline learning framework, which faces two core limitations: (1) heavy reliance on high-quality manual annotations for element grounding and action supervision, and (2) limited adaptability to dynamic and interactive environments. To address these limitations, we propose ZeroGUI, a scalable, online learning framework for automating GUI Agent training at Zero human cost. Specifically, ZeroGUI integrates (i) VLM-based automatic task generation to produce diverse training goals from the current environment state, (ii) VLM-based automatic reward estimation to assess task success without hand-crafted evaluation functions, and (iii) two-stage online reinforcement learning to continuously interact with and learn from GUI environments. Experiments on two advanced GUI Agents (UI-TARS and Aguvis) demonstrate that ZeroGUI significantly boosts performance across OSWorld and AndroidLab environments. The code is available at https://github.com/OpenGVLab/ZeroGUI.

https://huggingface.co/discussions/paper/68391354d8c153d346e1de1a